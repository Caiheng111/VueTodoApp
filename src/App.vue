<template>
  <div id="app">
 
    {msg}
  </div>
</template>

<script>


export default {
  name: 'App',
  components:{

  },
  data(){
    return {
      todo:[
        {
          id:1,
          title:'list1',
          completed: false
        },
        {
          id:2,
          title:'list2',
          completed: true
        },
        {
          id:3,
          title:'list3',
          completed: false
        },
      ]
    }
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
