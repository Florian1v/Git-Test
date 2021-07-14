<template>
  <div class="app">
    App.vue 我现在有 {{ total }}
    <child :money="tatal" v-on:update:money="total" ="$event" />
  </div>
</template>

<script>
import child from "./child.vue";
export default {
  components: { child },
  data() {
    return { tatal: 10000 };
  },
};
</script>

<style lang="scss" scoped>
</style>