<template>
  <transition>
    <div id="app">
      <!--<img src="./assets/logo.png">-->
      <keep-alive >
        <router-view v-if="$route.meta.keepAlive"></router-view>
      </keep-alive>
      <router-view v-if="!$route.meta.keepAlive"></router-view>
    </div>
  </transition>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  /*color: #2c3e50;*/
  /*width: 100%;*/
  /*height: 100%;*/
}
body{
  width:100%;
  height: 100%;
  background-color: #EDEAED;
}
</style>
