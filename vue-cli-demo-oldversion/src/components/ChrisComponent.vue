<template>
  <h1>{{ msg }}</h1>
</template>

<script>
export default {
  name: 'ChrisComp',
  data () {
    return {
      msg: '我的第一个 Vue-Cli'
    }
  }
}
</script>

<style scoped>
h1, h2 {
  color: blue;
  font-weight: normal;
}

</style>
