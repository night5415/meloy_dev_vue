<template>
  <video id="videoBG" autoplay muted loop>
    <source src="/media/code.mov" type="video/mp4" />
  </video>
</template>
<script>
export default {
  name: "Background",
  props: {
    msg: String,
    val: Number,
  },
  data() {
    return {
      number: 0,
    };
  },
  methods: {
    test() {
      alert();
    },
  },
};
</script>
<style scoped>
video {
  position: absolute;
  top: 0;
  left: 0;
  height: 100vh;
  width: 100vw;
  z-index: -1;
  object-fit: cover;
  object-position: center;
}
</style>