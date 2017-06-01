<template lang="pug">
  b-input-group
    b-form-checkbox(v-model="completed" value="yes" unchecked-value="no")
    b-form-input(v-model="action")
</template>

<script>
  export default {
    name: 'task',
    data () {
      return {
        completed: 'no',
        action: ''
      }
    }
  }
</script>
