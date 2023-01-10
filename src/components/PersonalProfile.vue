
<template>
 <div id = "profile">
<div>
    <img src = "@/assets/zachary_martin.jpg" id="mainphoto">
</div>
<div>
<h1 class = "maintitle" >
    Zachary Martin
</h1>
<h2 class = "secondtitle">
    Purdue '24, Computer Science Student, and Professional Googler
</h2>
<p class = "description">
    I am a junior at Purdue University with a major in Computer Science and a minor in Mathematics. 
</p>
<p class = "description">
    My interests/concentration is in softwart engineering, machine learning and security.
</p>
<br/>
<h2>
    Purdue College of Science, Purdue University
</h2>
<ul>
    <li>
        <p class = "description">
            Bachelor of Science in Computer Science
        </p>

    </li>

    <li>
        <p class = "description">
            Concentration in Software Engineering, Machine Learning and Security
        </p>

    </li>

    <li>
        <p class = "description">
            Minor in Mathematics
        </p>

    </li>
</ul>
</div>
</div>
</template>

<script>

export default {
    components: {
    }
}

</script>

<style scoped>

ul > * {
    margin-left: 10px;
}

#profile{
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    margin-top: 50px;
    flex-wrap: wrap;
    margin-left: 10px;
}
.maintitle{
    font-size: xx-large;
    font-weight: bold;

}



.description{
    font-size:large;
    font-weight: lighter;
}
#mainphoto {
    width: 300px;
    display: block;
    height: 300px;
    object-fit: cover;
    border-radius: 50%;
    padding: 8px;
    margin-right: 8px;
    
}

</style>