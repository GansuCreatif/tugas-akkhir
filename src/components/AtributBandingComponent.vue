<template>
    <div>
      <hr/>
      <h1>Kompentensi setiap Level:</h1>
      <hr/>
      <div id="warna" class="flex-container">
        <!-- Level Pemula -->
        <div class="flex-item" :class="textprimary">
          <p>Communication</p>
          <p>Collaboration</p>
          <p>Creativity</p>
          <p>Critical Thinking</p>
          <p>Menjadi Trainer Gamelab</p>
          <p>Logika dan Pemrograman</p>
          <p>HTML dan CSS</p>
        </div>
  
        <!-- Level Menengah -->
        <div class="flex-item" :class="textsecondary">
          <p>Javascript dan Jquery</p>
          <p>Bootstrap dan SASS</p>
          <p>Vue Javascript Framework</p>
        </div>
  
        <!-- Level Mahir -->
        <div class="flex-item" :class="textDanger">
          <p>ReactJs</p>
        </div>
  
        <!-- Noted -->
        <div class="flex-item-noted">
          <h2>Noted</h2>
          <p :class="textprimary">Level Pemula</p>
          <p :class="textsecondary">Menengah</p>
          <p :class="textDanger">Mahir</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'AtributBandingComponent',
    data() {
      return {
        textDanger: "text-danger",
        textprimary: "text-success",
        textsecondary: "text-warning",
        textthrid: "text-primary",
      };
    },
  };
  </script>
  
  <style scoped>
  .flex-container {
    display: flex;
  }
  
  .flex-item {
    flex: 1;
    padding: 10px;
  }
  
  .flex-item-noted {
    flex: 1;
    padding: 10px;
  }
  
  .text-success {
    color: green;
  }
  
  .text-warning {
    color: yellow;
  }
  
  .text-danger {
    color: red;
  }
  
  .text-primary {
    color: blue;
  }
  </style>
  