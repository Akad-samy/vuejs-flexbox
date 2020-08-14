<template>
  <div class="home">
    <Navbar/>
    <Section1/>
    <Section2/>
    <Section3/>
    <Section4/>
    <Section5/>
    <Section6/>
    <Navbar/>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Section1 from '@/components/Section1.vue'
import Section2 from '@/components/Section2.vue'
import Section3 from '@/components/Section3.vue'
import Section4 from '@/components/Section4.vue'
import Section5 from '@/components/Section5.vue'
import Section6 from '@/components/Section6.vue'

export default {
  name: 'Home',
  components: {
    Navbar,
    Section1,
    Section2,
    Section3,
    Section4,
    Section5,
    Section6,
  }
}
</script>
