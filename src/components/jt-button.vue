
<script>
export default {
  name: 'jumbotronButton',
  data(){
    return{
      text: 'Click Me'

    }
  }
}
</script>

<template>
    <button @click="text = 'Bravo'">{{text}}</button>    
</template>

<style scoped>
button{
  margin: 0 auto;
  line-height: 50px;
  padding:0 30px;
  color: white;
  background-color:rgb(81, 161, 188);
}

</style>