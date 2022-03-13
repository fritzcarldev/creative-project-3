<template>
<div>
  <AboutSection msg="Blog | Coming Soon" msg2="We are currently building the site, we will let you know when this feature is available" msg3="Our mission is to contribute to the development of Haiti with education, housing, and food"/>
  <ImageGrid :people="people"/>
  <FooterSection/>
</div>
</template>

<script>
// @ is an alias to /src
import ImageGrid from '@/components/ImageGrid.vue'
import AboutSection from '@/components/AboutSection.vue'
import FooterSection from '@/components/FooterSection.vue'

export default {
  name: 'HomeView',
  components: {
    ImageGrid,
    AboutSection,
    FooterSection
  },
  data() {
    return {
    }
  },
  computed: {
    people() {
      return this.$root.$data.people;
    }
  },
}
</script>
