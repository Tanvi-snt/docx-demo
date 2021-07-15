<template>
<div>
    <h1>List of ninjas</h1>
    <ul>
        <li v-for="ninja in ninjas"> {{ ninja }}</li>
    </ul>

 
</div>


</template>

<script>
export default {
 
  data () {
    return {
     ninjas:['tanvi', 'asmita', 'komal']
    }
  },
  //lifecycle hooks
  beforeCreate(){
    alert("beforeCreate");
  },
  created(){
    alert("created");
  },
  beforeMount(){
    alert("beforeMount");
  },
  mounted(){
    alert("mounted");
  },
  beforeUpdate(){
    alert("beforeUpdate");
  },
  updated(){
    alert("updated");
  }
}
</script>

<style scoped>

h1, h2 {
  font-weight: bold;
  color: blue;
}


</style>
