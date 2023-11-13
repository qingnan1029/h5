<template>
  <div id="app">
    
  </div>
</template>

<script>
 

export default {
  name: 'App',
  //components: {
  //  HelloWorld
  //},
  methods:{
    open(){
      window.location.href = 'atrustGovDingtalk.html';
    }
  },
  created () {
   // this.open();
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
