<template>
  <div>
    <header class="sticky top-0 bg-weather-primary shadow-lg">
      <nav 
        class="container flex flex-col sm:flex-row items-center
        gap-4 text-white py-6">
        <RouterLink :to="{ name: 'home' }">
          <div class="flex items-center gap-3">
            <i class="fas fa-sun text-2xl"></i>
            <p class="text-2xl">The Local Weather</p>
          </div>
        </RouterLink>

        <div class="flex gap-3 flex-1 justify-end">
          <i 
            class="fas fa-info-circle text-xl
          hover:text-weather-secondary duration-150
            cursor-pointer"></i>
          <i 
            class="fas fa-plus text-xl
          hover:text-weather-secondary duration-150
            cursor-pointer"></i>
        </div>

      </nav>
    </header>
  </div>
</template>

<script>
  import { RouterLink } from 'vue-router';
</script>

<style lang="scss" scoped>

</style>