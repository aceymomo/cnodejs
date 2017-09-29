<template>
  <div id="app">
    <cnodehead></cnodehead>
    <router-view name="main"></router-view>
  </div>
</template>

<script>
import cnodehead from '@/components/cnodeHead'
export default {
  name: 'app',
  components:{
    cnodehead,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
ul{
  margin: 0;
  padding: 0;
}
li{
  list-style: none;
}
</style>
