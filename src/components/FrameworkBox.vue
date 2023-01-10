<script setup>
import ItemBox from "./ItemBox.vue";
import IconVue from "./icons/IconVue.vue";
import IconReact from "./icons/IconReact.vue";
import IconFlutter from "./icons/IconFlutter.vue";
</script>

<template>
  <main class="wrapper">
    <ItemBox>
      <template #icon>
        <IconVue />
      </template>
    </ItemBox>

    <ItemBox>
        <template #icon>
            <IconReact/>
        </template>
    </ItemBox>

    <ItemBox>
        <template #icon>
            <IconFlutter/>
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
