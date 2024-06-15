<template>
  <div id="app" class="bg-gray-100 min-h-screen">
    <!-- Navigation bar or any other layout elements -->
    
    <router-view />

    <footer class="bg-gray-200 py-4 text-center">
      <p>&copy; 2024 Sophia Katsuno</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
  // You can add component options here
};
</script>

<style lang="css">
@tailwind base;
@tailwind components;
@tailwind utilities;

/* Additional custom styles can be added here */
</style>
