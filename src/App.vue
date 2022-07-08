<template>
  <learning-resources></learning-resources>
</template>

<script>
import LearningResources from './components/learning-resources/LearningResource.vue'

export default {
  name: 'App',
  components:{
    LearningResources
  },
  data(){
    // storedResources:[
    //   {
    //     id:'official-guide',
    //     title:'Official Guide',
        
    //   }
    // ]
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
