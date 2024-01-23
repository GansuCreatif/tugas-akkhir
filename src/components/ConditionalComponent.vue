<template>
    <div>
    <!-- Conditional Rendering -->
    <div v-if="showMessage">
      <p>{{ message }}</p>
      <img alt="Gansu" src="../assets/icon_bootcamp_gamelab.png">
    </div>
    <div v-else>
      <p>No message to show</p>
    </div>
  </div>
</template>
<script>
  export default {
    name: 'ConditionalComponent',
    data() {
        return {
            message: 'Profile Peserta',
            showMessage: Boolean,
        };
    },
  };
</script>
<style scoped>
    p{
        font-size: 100px;
    }
</style>  