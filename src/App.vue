
<body>

</body>
<template class="bod">
<div id="container">
  <h1 id="logotxt">Test-Site Solutions</h1>
  
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
      awesome: false
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
.bod {
  background-color: orange;
}
#logotext {
  text-shadow: 1px 1px 2px rgb(151, 62, 62);
}
#container {
  margin: auto;
  width: 150px;
  height: 300px;
  text-shadow: 1px 1px 2px rgb(213, 118, 45);
  
}
#logotext {
  text-shadow: 1px 1px 2px rgb(151, 62, 62);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
  margin-top: 1px;
  margin-left: 0%;
  margin-right: 0%;
  height: 670px;
  max-width: 100%;
  background-image: url('./assets/landskap2.jfif');
  border-style: solid;
  border-width: 3px;
  border-color: rgb(36, 35, 37);
}
.pic {
  max-width: 150%;
  height: 200px;
}

</style>
