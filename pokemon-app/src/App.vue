<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="p-14">
      <nav>
        <RouterLink to="/" class="flex justify-center text-4xl text-yellow-700">Pokemon Picker</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
