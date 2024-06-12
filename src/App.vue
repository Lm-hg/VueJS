<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

     <DataDisplay/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import DataDisplay from './components/Info.vue'


export default {
  name: 'App',
  components: {
    DataDisplay
  }
}
</script>


