<template>
  <div class="login">
    <login-panel />
  </div>
</template>

<script setup lang="ts">
import LoginPanel from "./cpns/panel.vue";
</script>

<style lang="less" scoped>
.login {
  display: flex;
  align-items: center;
  justify-content: center;

  width: 100%;
  height: 100%;
}
</style>
