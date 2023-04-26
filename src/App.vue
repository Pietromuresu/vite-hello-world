

<script>
    import AppTitle from "./components/AppTitle.vue"
    import AppHero from "./components/AppHero.vue"
    export default {
      name: "App",
      components: {
            AppTitle,
            AppHero
          },
      data(){
        return{

        }
      }
      
    }
</script>

<template>
<!-- Ora inserisco solo AppHero perchè l'ho montato in AppHero-->
  <AppHero />

</template>


<style>

</style>
