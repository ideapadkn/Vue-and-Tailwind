<template>
  <div>
    <Suspense>
      <AsyncCityView />
      <template #fallback>
        <p class="text-white text-xl pt-2 pl-2">Loading...</p>
      </template>
    </Suspense>
  </div>
</template>

<script setup>
import AsyncCityView from "../components/AsyncCityView.vue";
</script>
