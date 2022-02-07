<template>
  <h1>Les events: </h1>
  <Events />
  <h1>Les categorys: </h1>
   <Categorys />
</template>

<script>
import Events from './components/Events.vue'
import Categorys from './components/Categorys.vue'

export default {
  name: 'App',
  components: {
    Events, 
    Categorys
  }
}
console.log(process.env.VUE_APP_NOT_SECRET_CODE)
</script>
