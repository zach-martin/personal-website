<script setup>
import ItemBox from "./ItemBox.vue";
import IconGit from "./icons/IconGit.vue";
import IconCloudFlare from "./icons/IconCloudFlare.vue";
import IconFigma from "./icons/IconFigma.vue";
</script>

<template>
  <main class="wrapper">
    <ItemBox>
      <template #icon>
        <IconGit />
      </template>
    </ItemBox>

    <ItemBox>
      <template #icon>
        <IconCloudFlare />
      </template>
    </ItemBox>

    <ItemBox>
      <template #icon>
        <IconFigma />
      </template>
    </ItemBox>
  </main>
</template>

<style scoped>
.wrapper {
  display: flex;
  justify-content: center;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}
</style>
