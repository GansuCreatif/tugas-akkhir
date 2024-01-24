<template>
<section id="order">
<center><h2>Mereka Telah Belanja Anda Tidak Tertarik ?</h2></center>
<div class="container">
    <div class="row">
      <div class="col">
        <div class="card" style="width: 18rem;">
          <img src="https://unicorn-toys.com/wp-content/uploads/2021/05/WhatsApp-Image-2021-01-12-at-5.41.19-PM-1.jpeg" class="card-img-top" alt="...">
        </div>
      </div>
      <div class="col">
        <div class="card" style="width: 18rem;">
          <img src="https://unicorn-toys.com/wp-content/uploads/2021/05/WhatsApp-Image-2021-01-12-at-5.41.20-PM-1.jpeg" class="card-img-top" alt="...">
        </div>
      </div>
      <div class="col">
        <div class="card" style="width: 18rem;">
          <img src="https://unicorn-toys.com/wp-content/uploads/2021/05/WhatsApp-Image-2021-01-12-at-5.41.18-PM.jpeg" class="card-img-top" alt="...">
        </div>
      </div>
    </div>
</div>
</section>
</template>
<script>
     export default{
        name: 'OrderComponent',
    }
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@1,700&family=Oswald:wght@200;700&display=swap');
#order{
 background-color: #d0d0d0;
 margin-bottom: 40px;
    h2{
      font-size: 80px;
      color: #641E16;
      font-family: 'Chakra Petch', sans-serif;
      font-weight: bold;
  
    }
}
@media (min-width: 992px) {
    .rounded-lg-3 { border-radius: .3rem; }
    
    header {
      padding: 15px;
    }
  
    .nav-pills {
      flex-direction: row;
      align-items: center;
    }
  
    .nav-pills .nav-link {
      margin-bottom: 10px;
    }
  }
  
  @media (max-width: 992px) {
    .rounded-lg-3 { border-radius: .3rem; }
    section {
      padding: 60px 0;
    }
  }
  
  @media (max-width: 576px) {
    .rounded-lg-3 { border-radius: .3rem; }
    section {
      padding: 40px 0;
    }
  
    h1 {
      font-size: 1px;
    }
  
    h2 {
      font-size: 2rem;
    }
  
    p {
      font-size: 1rem;
    }
  
    footer {
      padding: 15px;
    }
    .nav-pills {
      flex-direction: column;
      align-items: center;
    }
  
    .nav-pills .nav-link {
      margin-bottom: 10px;
    }
    #faqs{
      flex-direction: column;
    }
  }

  @media (max-width:400px){
    .rounded-lg-3 { border-radius: .3rem; }
    section {
      padding: 40px 0;
    }
  
    h1 {
      font-size: 2.5rem;
    }
  
    h2 {
      font-size: 2rem;
    }
  
    p {
      font-size: 1rem;
    }
  
    footer {
      padding: 15px;
    }
    .nav-pills {
      flex-direction: column;
      align-items: center;
    }
  
    .nav-pills .nav-link {
      margin-bottom: 10px;
    }
  }
</style>