<template>
  <div>
    <h1>Home</h1>
    <Slider :slides="slides" />
  </div>
</template>

<script>
import Slider from '~/components/slider';
export default {
  name: 'Home',
  components: {
    Slider,
  },
};
</script>

<style></style>
