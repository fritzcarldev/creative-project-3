<template>
  <div>
    <AboutSection msg="Our Work" msg2="Foyer Coin Des Cieux is built on the foundation of love and service" msg3="Our mission is to contribute to the development of Haiti with education, housing, and food"/>
    <TeamInfo/>
    <FooterSection/>
  </div>
  
</template>

<script>
// @ is an alias to /src
import AboutSection from '@/components/AboutSection.vue'
import TeamInfo from '@/components/TeamInfo.vue'
import FooterSection from '@/components/FooterSection.vue'

export default {
  name: 'AboutView',
  components: {
    AboutSection,
    TeamInfo,
    FooterSection
  }
}
</script>
