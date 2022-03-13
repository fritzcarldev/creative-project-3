<template>
  <div class="about">
    <h1>{{ msg }}</h1>
    <p> {{ msg2 }}</p>
    <p> {{ msg3 }}</p>
  </div>
</template>

<script>
export default {
  name: 'AboutSection',
  props: {
    msg: String,
    msg2: String,
    msg3: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.about {
    padding: 50px;
    text-align: center;
    background-color: #F2B56B;
    color: black;
}
</style>
