<template>
  <div class="app">

<Todos />
  </div>
</template>


<script>

import Todos from "./components/Todos";

export default {
  name: 'App',
  components: {
    Todos



  }, 

  data () {

    return {

      todos: [{

        id: 1, 
        title: "Todo one", 
        completed: false

      }, 

      {
        id: 2, 
        title: "Todo Two", 
        completed: true
      }, 

      {

        id: 3, 
        title: "Todo Three", 
        completed: false
      }
      
      
      ]

    }
  }
}
</script>

<style>
.app {
    text-align: center;
}
</style>
