<template>
<div class="container">
  <HelloWorld />
  <SecondRoll />
  <ThirdRoll />
  <FourthRoll />
  <FifthRoll />
  <TixthRoll />
   <SeventhRoll />
   <EightRoll />
   <NinthRoll />
   <TenthRoll />
   <EleventhRoll />
  </div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import SecondRoll from './components/SecondRoll.vue'
import ThirdRoll from './components/ThirdRoll.vue'
import FourthRoll from './components/FourthRoll.vue'
import FifthRoll from './components/FifthRoll.vue'
import TixthRoll from './components/TixthRoll.vue'
import SeventhRoll from './components/SeventhRoll.vue'
import EightRoll from './components/EightRoll.vue'
import NinthRoll from './components/NinthRoll.vue'
import TenthRoll from './components/TenthRoll.vue'
import EleventhRoll from './components/EleventhRoll.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    SecondRoll,
    ThirdRoll,
    FourthRoll,
    FifthRoll,
    TixthRoll,
    SeventhRoll,
    EightRoll,
    NinthRoll,
    TenthRoll,
    EleventhRoll,
  },
 data() {
    return {
      name: ""
    }
  }
}
</script>

<style>
/* div{
  border: solid 2px red;
} */

</style>
