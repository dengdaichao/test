<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <input
      type="text"
      v-model="msg"
    >
    <!-- <input
      type="text"
      :value="msg"
      @input="msg = $event.target.value"
    > -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: ''
    }
  },
  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
