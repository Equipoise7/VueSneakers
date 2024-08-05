<template>
  <MyHello title="Кроссовки: Puma" :price="9500" is-added />
  <MyHello title="Кроссовки: Nike" :price="19500" />
  <MyHello title="Кроссовки: Reebok" :price="12500" />
</template>

<script setup>
import MyHello from './components/MyHello.vue'

</script>

<style scoped>

</style>
