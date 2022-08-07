
<body>

</body>
<template>
<div class="banner">
  <h1 class="projects">Projects</h1>
  <h1 class="about">About me</h1>
</div>
 <div class="wrapper">
  <h1 class="main">Student and hobby developer. <br>This is my webpage.</h1>
 </div>
<div class="about_wrap">
  <h1 class="about_banner">About me</h1>
</div>
<div class="about_main">
    <h1 class="about_paragraph">My name is Ådne Langedal, I am a 23 year old male
    studying information science at the University of Bergen. I work with a variety of
    different technologies and enjoy learning new things.</h1>
</div>
<div class="project_wrapper">
  <h1 class="project_banner">Projects</h1>
</div>
<div class="project_box_wrapper">
  <h1 class="project_box">lore ipsum where this this approimately how many words to be used in this box</h1>
</div>
<div>
  <span class="arrow_right">
<img src=".\assets\arrow_forward.png">
</span>
</div>
<div>
  <span class="arrow_left">
<img src=".\assets\arrow_back.png">
</span>
</div>
</template>

<script>


export default {
  //name: 'App',
  components: {
    //HelloWorld
  },
  data() {
    return {
      home: 'true',
      about: 'false',
      proj: 'false'
    }
  },
  methods: {
    toggle_about() {
      this.about = true
      this.home = false
      this.proj = false
    },
}
}

</script>

<style>
.arrow_right {
  position: relative;
  top: -140px;
  right: 20%;
}
.arrow_left {
  position: relative;
  top: -190px;
  margin-right: 75%;
}
.project_box {
  max-width: 40%;
  min-width: 40%;
  min-height: 200px;
  border-color: black;
  border-style: solid;
  text-align: center;
  padding-top: 5%;
  font-size: 150%; 
}
.project_box_wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.project_wrapper {
  margin-top: 20%;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.project_banner {
  background-color: black;
  color: aliceblue;
}
.about_main {
  padding: 5px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.about_paragraph {
  width: 70%;
  background-color: black;
  color: aliceblue;
  text-align: center;
}
.about_banner {
  padding: 5px;
  background-color: black;
  color: aliceblue;
  font-size: 250%;
}
.about_wrap {
  margin-top: 40%;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.projects {
  background-color: black;
  color: aliceblue;
}
.home_banner {
  padding: 10px;
  background-color: black;
  color: aliceblue;
  border-color: gray;
  border-style: solid;
}
.banner {
  display: flex;
  flex-wrap: wrap;
}
.about {
  padding: 10px;
  background-color: black;
  color: aliceblue;
  border-color: gray;
  border-style: solid;
}
.projects {
  padding: 10px;
  background-color: black;
  color: aliceblue;
  border-color: gray;
  border-style: solid;

}
.wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.main {
  font-size: 300%;
  background: black;
  margin-top: 15%;
  margin-right: 20%;
  min-height: 40%;
  color: white;
  font-family: Avenir;
  border-color: grey;
  border-style: solid;  
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
  margin-top: 0px;
  margin-left: 0%;
  margin-right: 0%;
  height: 620px;
  max-width: 100%;
  background-color: whitesmoke;
  border-style: solid;
  border-width: 3px;
  border-color: rgb(36, 35, 37);
  position: relative;
}
@media only screen and (max-width: 500px) {
  .arrow_right {
  position: relative;
  top: -130px;
  right: 2%;
  border-color: blue;
  border-style: solid;
  }
}
@media only screen and (max-width: 500px) {
  .arrow_left {
  position: relative;
  top: -175px;
  right: 10%;
  border-color: blue;
  border-style: solid;
  }
}
@media only screen and (max-width: 500px) {
  .project_box {
  max-width: 60%;
  min-width: 40%;
  min-height: 200px;
  border-color: black;
  border-style: solid;
  text-align: center;
  padding-top: 5%;
  font-size: 150%; 
  }
}
</style>
