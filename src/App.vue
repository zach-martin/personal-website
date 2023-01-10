<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import IconBar from "./components/IconBar.vue";
import FrameworkBox from "./components/FrameworkBox.vue";
import DevToolsBox from "./components/DevToolsBox.vue";
import PersonalProfile from "./components/PersonalProfile.vue";
import WorkExperience from "./components/WorkExperience.vue";
import Navbar from "./components/Navbar.vue";
import SkillsProfile from "./components/SkillsProfile.vue"
</script>

<template>
  <div>
   <Navbar/>
  <main class = "container">
  <PersonalProfile/>
  <WorkExperience/>
  <SkillsProfile/>
  <div>
  <div>
  <p class="text-icons">
    Programming Languages
  </p>
  <IconBar />
  </div>
  <div>
  <p class="text-icons">
    Frameworks
  </p>
  <FrameworkBox />
  </div>
  <div>
    <p class="text-icons">
    Development Tools
  </p>
  <DevToolsBox />
  </div>
  </div>
  </main>
  </div>
</template>

<style scoped>

.text-icons{
      text-align: center;
      font-size: x-large;
      font-weight: bold;
      padding: 50px;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  main.container{
    display: flex;
    flex-direction: column;
    justify-content: space-between
    }

    main.container > * {
      padding: 100px;

    }



}
</style>
