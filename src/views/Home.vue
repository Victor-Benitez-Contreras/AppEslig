<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Chupalo x1000"/>
    <miComponente></miComponente>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import miComponente from '@/components/miComponente.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
    miComponente
  }
}
</script>
