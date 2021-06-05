<template>
  <div class="hello">
    <div style="background: red;">
      <MiComponte></MiComponte>
    </div>
    <hr/>
    <h1>{{ msg }}</h1>
    <h2>{{ holaMundo }}</h2>
  </div>
</template>

<script>

import MiComponte from './MiComponte.vue'

export default {
  name: 'HelloWorld',
  components: {
    MiComponte
  },
  props: {
    msg: String
  },
  data(){
    return {
      holaMundo: "Hola mundo desde componente!!"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
