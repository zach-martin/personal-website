<template>

  <div>
  <h1 class="skills-text">
    Skills
  </h1>
  <p class = "sub-text">
    Below are some of my skills, and I'm always looking to learn more. 
  </p>
  </div>
  <br>
  <br>
  <br>
  <div class="skills">
    <div>
    <img src = "@/assets/communication_skills.svg" class="skills"/>
    <p class="text-name">
       Communication
    </p>
    <p class="sub-text" > 
      Through my experience as a Sales Associate, employee at Avalon Labs and my part-time job of being a waiter, I have developed communication skills that allow me correctly convey my thoughts and ideas.
    </p>
    </div>
    <div>
      <img src = "@/assets/algorithm-icon.svg" class="skills"/>
    <p class="text-name">
        Analysis
    </p>
    <p class = "sub-text">
      I have significant experience with analysis through my Purdue courses, I have had to analyze algorithms, mathematical equations, code and more. Through all of this, I believe my analysis skills has become one of my best attributes. 
    </p>
    </div>
    <div>
    <img src = "@/assets/creativity-icon.svg" class="skills"/>
    <p class="text-name">
        Creativity
    </p>
    <p class="sub-text">
      In all aspects of my life, no matter if it is work, school or my daily life, I believe I use my creativity to find solutions to difficult problems or find more efficient ways to do somethings.
    </p>
    </div>
    </div>

</template>

<script>

</script>

<style>

.skills-text {
      text-align: center;
      font-size: xx-large;
      font-weight: bold;
    }

 p.sub-text{
    text-align: center;
    font-size: large;
    font-weight: lighter;
    }

div.skills{
    display: flex;
    justify-content: space-around;
    text-align: center;
}

div.skills > * {
  width: 100%;
  padding: 10px;
}

img.skills {
  max-width: 96px;
}

p.text-name{
      text-align: center;
      font-size: x-large;
      font-weight: bold;
}


</style>