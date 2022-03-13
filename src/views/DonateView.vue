<template>
<div>
  <AboutSection msg="Donate | Coming Soon" msg2="There are many ways to donate to this organization, as we build this website we will let you know!" msg3="Our mission is to contribute to the development of Haiti with education, housing, and food"/>
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
