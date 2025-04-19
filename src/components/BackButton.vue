<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <section>
    <div class="container m-auto px-6 py-6">
      <RouterLInk
        to="/jobs"
        class="flex items-center text-green-500 hover:text-green-600"
      >
        <i class="pi pi-arrow-circle-left mr-3"></i> Back to Job Listings
      </RouterLInk>
    </div>
  </section>
</template>
