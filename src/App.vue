
<template>
  <div id ="app">
      <div>
        <router-link to="/page1">Page1</router-link>
        <router-link to="/page2">Page2</router-link>
      </div>
      <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      msg: 'welcome to Your vue.js App'
    }
  }
}
</script>

<style>
/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
