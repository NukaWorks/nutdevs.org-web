<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style scoped lang="scss">
.hello {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;

  &, h1 {
    font-size: calc(1rem + 5vw);
  }
}
</style>
