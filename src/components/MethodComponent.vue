<template>
    <div>
      <hr />
      <div class="alert" :class="{ 'show': isAlertVisible }">
        {{ alertMessage }}
      </div>
      <button class="btn btn-primary w-25" @click="showWelcomeMessage">Klik Aku dong !</button>
      <hr />
    </div>
  </template>
  
  <script>
  export default {
    name: "MethodComponent",
    data() {
      return {
        isAlertVisible: false,
        alertMessage: "Ganjar Sugiharto peserta Bootcamp kelas Front End di GameLab",
      };
    },
    methods: {
      toggleAlert() {
        this.isAlertVisible = !this.isAlertVisible;
      },
      showWelcomeMessage() {
        this.toggleAlert();
      },
    },
  };
  </script>
  
  <style scoped>
  /* Gaya CSS untuk komponen */
  .alert {
    background-color: #f8d7da;
    color: #721c24;
    padding: 10px;
    border: 1px solid #f5c6cb;
    border-radius: 5px;
    opacity: 0;
    transition: opacity 0.5s;
    cursor: pointer;
  }
  
  .show {
    opacity: 1;
  }
  </style>
  