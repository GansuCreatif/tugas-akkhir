<template>
<section id="faqs">
  <center><h1>Pertanyaan seputar Gunpla</h1></center>
  <div class="container col-xxl-8 px-4 py-5">
    <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
        <div class="col-12 col-lg-6">
            <img src="https://unicorn-toys.com/wp-content/uploads/2021/08/UNICORN-PHENEX.png" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
        </div>
        <div class="col-lg-6">
          <div class="accordion accordion-flush" id="accordionFlushExample">
            <div class="accordion-item">
              <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                  Apa Itu Gunpla
                </button>
              </h2>
              <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                <div class="accordion-body">Gunpla adalah singkatan dari "Gundam Plastic Model," yang merujuk pada model-kit plastik yang dirancang untuk membangun model robot dari waralaba Gundam. Gundam sendiri adalah salah satu seri anime dan waralaba media Jepang yang berfokus pada cerita-cerita tentang robot raksasa humanoid yang dikenal sebagai "Mobile Suits.".</div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                  Ada Model Apa Saja Gunpla
                </button>
              </h2>
              <div id="flush-collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                <div class="accordion-body">Berbagai jenis dan skala Gunpla tersedia, mulai dari skala kecil (SD - Super Deformed) hingga skala besar (MG - Master Grade, RG - Real Grade, HG - High Grade).</div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                  Apakah Gunpla di Toko Original
                </button>
              </h2>
              <div id="flush-collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                <div class="accordion-body">Gunpla yang dijual di toko ini semua original 100% BANDAI.</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</section>
</template>
<script>
    export default {
        namme: 'FAQsComponent'
    };
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@1,700&family=Oswald:wght@200;700&display=swap');
#faqs{
    background-color: #dadfde;
    margin: 100px;
    h1{
      font-size: 80px;
      color: #641E16;
      font-family: 'Chakra Petch', sans-serif;
      font-weight: bold;
  
    }
  }
</style>