<template>
<div>
    <h1>{{ name }}</h1>
   <ninjas></ninjas>
</div>


</template>

<script>
import Ninjas from './Ninjas.vue'
export default {
  components: { Ninjas },

 
  data () {
   
    return {
      name: 'I am tanvi lanjekar'
    }
  },
  methods:{
    greeting:function(){
      return 'This is my first vue cli demo!!!!'
    }
  }
}
</script>



<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: bold;
  color:green;
}


</style>
