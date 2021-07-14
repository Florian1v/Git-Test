<template>
  <div>
    <input type="text" v-model="name" />
    <br />

    <login v-bind:title="name"></login>
  </div>
</template>

<script>
const login = {
  template: "",
};
</script>

<style lang="scss" scoped>
</style>