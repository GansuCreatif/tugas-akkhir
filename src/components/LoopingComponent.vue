<template>
    <hr/>
    <div id="bio">
      <h2>Detail Biodata Ganjar Sugiharto</h2>
      <p v-for="(value, key, index) in character" :key="index">
        {{index + 1}} {{key}}: {{value}}
      </p>
    </div>
    <hr/>
    <div id="kompetens">
      <h2>Daftar Kelas yang diambil SoftSkill</h2>
      <!-- Gunakan v-for untuk melakukan perulangan -->
      <p v-for="(kompentensi, index) in kompetensis" :key="index">
        {{index + 1}}.{{kompentensi}}
      </p>
    </div>
    <hr/>
    <div id="kompeteng">
      <h2>Daftar Kelas yang diambil HardSkill</h2>
      <!-- Gunakan v-for untuk melakukan perulangan -->
      <p v-for="(kompenteng, index) in kompetensig" :key="index">
        {{index + 1}}.{{kompenteng}}
      </p>
    </div>
    <hr>
  </template>
  
  <script>
  export default {
    name: 'LoopingComponent',
    data() {
    return {
            kompetensis: [
                'Communication', 
                'Collaboration', 
                'Critical Thinking',
                'Creativity',
                'Menjadi Trainer Gamelab',
                
            ],
            kompetensig: [
                'Logika dan Pemograman',
                'HTML dan CSS',
                'Javascript dan Jquery',
                'Bootstrap dan SASS',
                'Vue Javascript Framework',
                'ReactJs',
            ],
            character: {
            nama: 'Ganjar Sugiharto',
            umur: 25,
            kelas: 'Bootcamp Front End'
         }
        };
    }
  };
  </script>
  