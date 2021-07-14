<template>
  <div>
    <button @click="show">打开弹窗</button>
    <idialog @visibleState="changeVisible" :visible="display"
  </div>
</template>

<script>
export default {
  name: "idialog",
};
</script>

<style lang="scss" scoped>
</style>