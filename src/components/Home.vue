<template>
  <div class="home" style="text-align: center;">
    <h1>Welcome to Our Website</h1>
    <p class="subtitle">This is the main page of our application</p>

    <div class="card">
      <h2>Featured Content</h2>
      <p>Discover amazing features we offer to our users.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeView'
}
</script>

<style scoped>
.home {
  max-width: 800px;
  margin: 0 auto;
}

.subtitle {
  color: #666;
  margin-bottom: 30px;
}

.card {
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  margin-top: 20px;
}
</style>