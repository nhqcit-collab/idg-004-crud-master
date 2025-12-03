<template>
  <div class="p-6 max-w-4xl mx-auto bg-gray-100">
    <Navigation />
    <router-view />
  </div>
</template>
<script>
import Navigation from '@/components/Navigation.vue';
export default {
  components: {
    Navigation
  }
}
</script>