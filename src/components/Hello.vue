<template lang="pug">
  div.hello
    h1 {{ msg }}
    b-card
      task-list
</template>

<script>
  import TaskList from '@/components/TaskList'
  export default {
    name: 'hello',
    data () {
      return {
        msg: 'Vue-todo and you can too!'
      }
    },
    components: { TaskList }
  }
</script>

<style lang="sass" scoped>
  h1, h2
    font-weight: normal

  ul
    list-style-type: none
    padding: 0

  li
    display: inline-block
    margin: 0 10px

  a
    color: #42b983
</style>
