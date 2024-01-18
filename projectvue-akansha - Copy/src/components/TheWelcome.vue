<template>
  <div class="child">
    <p>Prop1: {{ prop1 }}</p>
    <p>Prop2: {{ prop2 }}</p>
    <p>Prop3: {{ prop3.object }}</p>
  </div>
</template>

<script>
export default {
  props: {
    prop1: String,
    prop2: Number,
    prop3: Object,
  },
};
</script>