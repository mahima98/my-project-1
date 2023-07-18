<script setup>
import Header from "./components/Header.vue";
</script>

<template>
  <Header />
  <Transition name="fade" mode="out-in">
    <router-view></router-view>
  </Transition>
</template>
<style>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s ease;
}

.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
</style>
