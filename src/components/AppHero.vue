<script>
import AppTitle from "./AppTitle.vue"
export default {
  name: "AppHero",
  data(){
    return{

    }
  },

  components:{
    AppTitle
  }
}
</script>

<template>
  <div>
    <AppTitle/>
  </div>
</template>

<style scoped>
div{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100vw;
  height: 500px;
  background-image: url("../assets/Img/jumbotron-bg.webp");
}
</style>