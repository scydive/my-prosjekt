
<body>

</body>
<template>
 <div class="wrapper">
  <h1 class="about">About me</h1>
  <h1 class="projects">Projects</h1>
  <h1 class="main">Student and hobby developer. <br>This is my webpage.</h1>
 </div>
    
</template>

<script>

//import HelloWorld from './components/HelloWorld.vue'

export default {
  //name: 'App',
  components: {
    //HelloWorld
  },
  data() {
    return {
      temp: '1',
    }
  },
  methods: {
    inc() {
      this.temp++
    }
}
}

</script>

<style>
.wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;


}
.main {
  font-size: 300%;
  background: black;
  margin-top: 30%;
  margin-right: 30%;
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
  height: 670px;
  max-width: 100%;
  background-color: whitesmoke;
  border-style: solid;
  border-width: 3px;
  border-color: rgb(36, 35, 37);
  position: relative;
}
@media all and (min-width: 620px) {
  .main {
    margin-top: 20%;
    margin-right: 20%;
    min-height: 40%;

  }
}
@media all and (max-width: 400px) {
  .main {
    margin-top: 20%;
    min-height: 40%;
    border-color: white;
  }
}

</style>
