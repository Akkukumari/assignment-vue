<template>
  <div class="home">
    <TheWelcome :prop1="value1" :prop2="value2" :prop3="value3" />
  </div>
</template>

<script>
import TheWelcome from '../components/TheWelcome.vue';

export default {
  components: {
    TheWelcome,
  },
  data() {
    return {
      value1: 'Akansha',
      value2: 24,
      value3: { object: 'masai school' },
    };
  },
};
</script>
<style>
@media (min-width: 1024px) {
  .home {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

