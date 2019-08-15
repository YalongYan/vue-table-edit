<template>
  <div id="app">
    <Table/>
  </div>
</template>

<script>
import Table from './components/Table'

export default {
  name: 'app',
  data () {
    return {
    }
  },
  components: {
    Table
  }
}
</script>

<style lang="scss">
ul, li {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
</style>
