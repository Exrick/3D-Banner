<template>
  <div class="home">
    <Banner3D/>
  </div>
</template>

<script>
import Banner3D from './components/Banner3D'

export default {
  name: 'App',
  components: {
    Banner3D
  }
}
</script>

<style>
.home {
  display: flex;
  flex-direction: column;
}
</style>
