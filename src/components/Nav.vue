<template>
  <nav>
    <div>HTML</div>
    <div>JavaScript</div>
    <div>CSS</div>
  </nav>
</template>

<script>
export default {
  name: "navigation",
  data() {
    return {
      number: 0,
    };
  },
  methods: {},
};
</script>

<style scoped>
nav {
  display: flex;
  flex-wrap: nowrap;
  background-color: DodgerBlue;
}
nav div {
  flex-grow: 4;
  margin: 10px;
  align-content: center;
  text-align: center;
  color: #fff;
  font-size: 1.2rem;
}
nav div:nth-child(-n + 2) {
  border-right: 1px solid #fff;
}
</style>