
<body>

</body>
<template>
<div id="container">
  <img id="cover" src='./assets/placeholder2.jpg'>
  <h1 @click="rand" id="info_text">Young hobby developer and student, this is my portfolio website.</h1>
  
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
#container #info_text {
  position: relative;
  top: -230px;
  right: -160px;
  width: 240px;

}
#container #cover {
  width: 150px;
  margin-right: 0%;
  margin-top: 0%;
  position: relative;
  right: 31.5%;

}

#container {
  margin-left: 25%;
  margin-top: 13%;
  width: 400px;
  height: 272px;
  border-style: solid;
  border-color: rgb(58, 61, 61);
  border-width: 5px;
  background-color: black;
  color: azure;
  font-family: "Ibarra+Real+Nova", serif;
  font-size: small;
  text-align: center;
  padding: 0%;
  
  
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
  background-image: url(./assets/notowned.jpg);
  border-style: solid;
  border-width: 3px;
  border-color: rgb(36, 35, 37);
}


</style>
