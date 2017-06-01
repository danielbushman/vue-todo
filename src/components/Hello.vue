<template lang="pug">
  div.hello
    h1 {{ msg }}
    h2 Now with Pug!
    ul
      li
        b-button(variant="primary") Hello world

</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit styles to this component only -->
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
