<template>
  <div class="child">
    {{ money }}
    <button @click="$emit('update:money', money - 100">
      <span>花钱</span>
    </button>
  </div>
</template>

<script>
export default {
  props: ["money"],
};
</script>

<style lang="scss" scoped>
</style>