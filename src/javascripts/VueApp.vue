<template>
  <div>
    <p>webpack practice</p>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data: () => {
    console.log("Vue is installed");
    return {
      message: "Hey, this is Vue",
    };
  },
};
</script>

<style scoped>
p {
  color: green;
  text-align: center;
}
</style>
