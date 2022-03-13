<template>
  <div class="row">
            <div class="column">
              <img src="/images/people/IMG_0006.JPG">
              <img src="/images/people/IMG_0005.JPG">
              <img src="/images/people/IMG_0007.JPG">
              <img src="/images/people/IMG_0008.JPG">
              <img src="/images/people/IMG_0003.JPG">
            </div>
            <div class="column">
                <img src="/images/people/IMG_0002.JPG">
                <img src="/images/people/IMG_0003.JPG">
                <img src="/images/people/IMG_0004.JPG">
                <img src="/images/people/IMG_0005.JPG">
                <img src="/images/people/IMG_0003.JPG">
              </div>
              <div class="column">
                <img src="/images/people/IMG_0007.JPG">
                <img src="/images/people/IMG_0005.JPG">
                <img src="/images/people/IMG_0007.JPG">
                <img src="/images/people/IMG_0003.JPG">
                <img src="/images/people/IMG_0009.JPG">
              </div>
              <div class="column">
                <img src="/images/people/IMG_0008.JPG">
                <img src="/images/people/IMG_0005.JPG">
                <img src="/images/people/IMG_0007.JPG">
                <img src="/images/people/IMG_0008.JPG">
                <img src="/images/people/IMG_0009.JPG">
              </div>
          </div>
</template>

<script>
export default {
  name: 'ImageGrid',
  props: {
    people: Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
    width: 100%;
    height: auto;
}


.row {
    display: flex;
    flex-wrap: wrap;
    padding: 0 4px;
  }
  

  .column {
    flex: 25%;
    max-width: 25%;
    padding: 0 4px;
  }
  
  .column img {
    margin-top: 8px;
    vertical-align: middle;
    width: 100%;
  }
  
  @media screen and (max-width: 800px) {
    .column {
      flex: 50%;
      max-width: 50%;
    }
  }
  
  @media screen and (max-width: 600px) {
    .column {
      flex: 100%;
      max-width: 100%;
    }
  }
</style>
