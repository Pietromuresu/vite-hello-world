<script>
import AppTitle from "./AppTitle.vue"
import jtButton from "./jt-button.vue";
export default {
  name: "AppHero",
  data(){
    return{

    }
  },

  components:{
    AppTitle,
    jtButton
  }
}
</script>

<template>
  <div>
    <AppTitle/>
    <jt-button/>
  </div>
</template>

<style scoped>
div{
  text-align: center;
  padding-top: 50px;
  width: 100vw;
  height: 500px;
  background-image: url("../assets/Img/jumbotron-bg.webp");
}


</style>