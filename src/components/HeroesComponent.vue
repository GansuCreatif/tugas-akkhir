<template>
        <div class="container col-xxl-8 px-4 py-5">
            <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
                <div class="col-12 col-lg-6">
                    <img src="https://unicorn-toys.com/wp-content/uploads/2021/08/UNICORN-PHENEX.png" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
                </div>
             <div class="col-lg-6">
                        <h1 class="display-5 fw-bold lh-1 mb-3">Gansu Toys</h1>
                        <p class="lead">Belanja di Gansu Toys DIJAMIN ASIK! Tersedia varian Gunpla dari yang termurah sampai yang super Premium...</p>
                    <div class="d-grid gap-5 d-md-flex justify-content-md-start">
                        <a class="btn btn-primary btn-lg px-4 mx-2" href="#katalog">Lihat Katalog Produk</a>
                    </div>
                </div>
            </div>
        </div>
</template>
<script>
     export default{
        name: 'HeroesComponent',
    } 
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@1,700&family=Oswald:wght@200;700&display=swap');
.container{
    margin-top: 40px;
    margin-bottom: 40px;
    background-image:url('https://shop.bandai.com/media/magefan_blog/04_12.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    h1{
      font-size: 80px;
      color: #641E16;
      font-family: 'Chakra Petch', sans-serif;
      font-weight: bold;
  
    }
    p{
      font-size: 80x;
      font-family: 'Chakra Petch', sans-serif;
      color:#000000;
      font-weight: bold;
    }
}
</style>