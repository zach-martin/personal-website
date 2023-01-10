<script setup>
import ItemBox from "./ItemBox.vue";
import IconC from "./icons/IconC.vue";
import IconJava from "./icons/IconJava.vue";
import IconCplus from "./icons/IconCplus.vue";
import IconPython from "./icons/IconPython.vue";
import IconJavaScript from "./icons/IconJavaScript.vue";
import IconTypeScriptVue from "./icons/IconTypeScript.vue";
import IconHTMLVue from "./icons/IconHTML.vue";
import IconCSS from "./icons/IconCSS.vue";
import IconR from "./icons/IconR.vue";
import IconSQLvue from "./icons/IconSQL.vue";
import IconNeo4jVue from "./icons/IconNeo4j.vue";
</script>

<template>
  
  <div class="wrapper">

  <ItemBox>
    <template #icon>
      <IconC />
    </template>
  </ItemBox>

  <ItemBox>
    <template #icon>
      <IconJava />
    </template>
  </ItemBox>

  <ItemBox>
    <template #icon>
      <IconCplus />
    </template>
  </ItemBox>

  <ItemBox>
    <template #icon>
      <IconPython />
    </template>
  </ItemBox>

  <ItemBox>
    <template #icon>
      <IconJavaScript />
    </template>
  </ItemBox>

  <ItemBox>
    <template #icon>
      <IconTypeScriptVue />
    </template>
  </ItemBox>

  <ItemBox>
    <template #icon>
      <IconHTMLVue />
    </template>
  </ItemBox>

  <ItemBox>
    <template #icon>
      <IconCSS />
    </template>
  </ItemBox>

  <ItemBox>

    <template #icon>
      <IconR/>
    </template>

  </ItemBox>

<ItemBox>

  <template #icon>
    <IconSQLvue/>
  </template>

</ItemBox>

<ItemBox>
  <template #icon>
    <IconNeo4jVue/>
  </template>
</ItemBox>
</div>

</template>

<style scoped>

.wrapper {
  display: flex;
  position: relative;
  justify-content: center;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}



</style>
