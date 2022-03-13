<template>
<div>
  <AboutSection msg="Our Work" msg2="Foyer Coin Des Cieux is built on the foundation of love and service" msg3="Our mission is to contribute to the development of Haiti with education, housing, and food"/>
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
