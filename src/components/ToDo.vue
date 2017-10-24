<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
  export default {
    name: 'ToDo',
    data () {
      return {
        title: 'TO DO APP'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1 {
    font-weight: normal;
  }
</style>
