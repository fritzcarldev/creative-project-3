<template>
  <div class="footer">If you have any questions, use this <a class =" github" href="https://github.com/fritzcarldev/creative-project.git">GitHub</a></div>
</template>

<script>
export default {
  name: 'FooterSection',
  props: {
    msg: String,
    msg2: String,
    msg3: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
    color: #EAEDF0;
    position: sticky;
    right: 0;
    bottom: 0;
    left: 0;
    padding: 1rem;
    background-color: #3B848C;
    text-align: center;
  }
.github {
      color: #F2B56B;
  }
</style>
