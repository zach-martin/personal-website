<script setup>
import IconLinkedIn from './icons/IconLinkedIn.vue';
import IconGithub from './icons/IconGithub.vue';
</script>

<template>
    <div class = "container-navbar">
    <h2>
        Zachary Martin
    </h2>
    <div>
    
    <IconLinkedIn/>

    <IconGithub/>
    </div>
    </div>
</template>

<style scoped>
.container-navbar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: fixed;
    position: -webkit-sticky;
    top: 10px;
    z-index: 2;
    left: 0;
    top: 0;
    width: 100%;
    padding-left: 20px;
    padding-right: 20px;
    background-color: var(--color-background-mute);
}




h2{
    padding-right:10px
}
</style>