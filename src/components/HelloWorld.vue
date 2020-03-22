<template>
  <div class="hello">
    <marquee-text :duration="15">
      <h1>{{ msg }}</h1>
    </marquee-text>
  </div>
</template>

<script>
import MarqueeText from 'vue-marquee-text-component'

export default {
  name: 'HelloWorld',
  components: {
    MarqueeText
  },
  data () {
    return {
      msg: 'This website is currently under development. Please come back later.'
    }
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
