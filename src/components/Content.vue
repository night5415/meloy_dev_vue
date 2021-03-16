<template>
  <main>
    <Nav />
  </main>
</template>
<script>
import Nav from "./Nav";
export default {
  name: "Content",
  components: {
    Nav,
  },
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
main {
  background: gray;
  height: 100vh;
  width: 75vw;
  margin: 0 auto;
}
</style>