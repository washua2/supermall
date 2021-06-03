<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>
<script>
  export default {
    name:"app",
    data(){
      return{

      }
    },
    components:{

    }
  }


</script>

<style lang="scss">
@import "assets/css/base.css";
#app {
  text-align:center;
}

</style>
