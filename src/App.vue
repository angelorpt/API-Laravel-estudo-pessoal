<template>
  <div>
    <nav-bar cor="green darken-1" url="#" logo="Social">

    </nav-bar>
    <router-view/>
  </div>
</template>

<script>

  import NavBar from '@/components/layouts/NavBar'

  export default {
    name: 'app',
    components: {
      NavBar
    }
  }
  
</script>

<style>

</style>
