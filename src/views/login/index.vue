<template>
  <div>
    Login

    <a-button type="primary">登录</a-button>

    <div>
      当前的值为 {{ num }}
      <a-button type="primary" @click="num++">+1</a-button>
    </div>
  </div>
</template>

<script setup lang="ts">
const num = ref(0)
</script>

<style scoped></style>
