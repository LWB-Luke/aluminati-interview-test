<template>
  <div id="app">
    <input type="number" v-model="limit" max="100"/> <!-- Limit input to 100 -->
    <Numbers/>
  </div>
</template>

<script>
import Numbers from '@/components/Numbers';

export default {
  name: 'App',
  components: {Numbers},
  data()
  {
    return {
      limit: 100
    }
  }
}
</script>

<style scoped>
</style>
