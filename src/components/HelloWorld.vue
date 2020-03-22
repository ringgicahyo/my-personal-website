<template>
  <div class="hello">
    <marquee-text>
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
      msg: '| This website is currently under development. Thank you for visiting. Please come back later. |'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: 500;
  font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.hello{
  width: 80%;
  margin: auto;
}
</style>
