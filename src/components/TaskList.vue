<template lang="pug">
  ul
    li(v-for="task in tasks")
      task(:completed="task.completed")
</template>

<script>
  import Task from '@/components/Task'
  export default {
    name: 'task-list',
    data () {
      return {
        tasks: [
          {completed: 'yes', action: 'just do it'},
          {completed: 'no', action: 'run for pres'}
        ]
      }
    },
    components: { Task }
  }
</script>

<style lang="sass">
</style>
