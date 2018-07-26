<template>
  <v-app id="HelloWorld">
    <myheader></myheader>
    <v-container>
      HelloWorld
    </v-container>
  </v-app>
</template>
<script>
import Header from '@/components/header'
export default {
  name: 'HelloWorld',
  components: {
    'myheader': Header
  },
  data () {
    return {}
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
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
