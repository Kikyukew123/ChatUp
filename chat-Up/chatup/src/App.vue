<template>

  <NavBarView/>
  <router-view/>
</template>

<script > 
import NavBarView from './components/NavBarView.vue'
export default{
    components: { NavBarView },
    name: 'App'
  }
</script>



