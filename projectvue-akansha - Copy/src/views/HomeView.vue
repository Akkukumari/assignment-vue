<template>
  <div class="parent">
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
      value1: 'Data for prop1',
      value2: 42,
      value3: { object: 'property' },
    };
  },
};
</script>

