<template>
  <div class="container">
    <header class="d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-3 mb-4 border-bottom">
      <div class="col-md-3 mb-2 mb-md-0">
        <a href="/" class="d-inline-flex link-body-emphasis text-decoration-none">
             <img alt="Vue logo" src="https://unicorn-toys.com/wp-content/uploads/2021/08/UNICORN-PHENEX.png" width="120" height="120">
        </a>
      </div>

      <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
        <li><a href="#" class="nav-link px-2">Home</a></li>
        <li><a href="#" class="nav-link px-2">Products</a></li>
        <li><a href="#" class="nav-link px-2">Testimony</a></li>
        <li><a href="#" class="nav-link px-2">FAQs</a></li>
        <li><a href="#" class="nav-link px-2">About</a></li>
      </ul>

      <div class="col-md-3 text-end">
        <button type="button" class="btn btn-outline-primary me-2" data-bs-toggle="modal" data-bs-target="#loginModal">Login</button>
        <button type="button" class="btn btn-primary">Sign-up</button>
      </div>
    </header>
    <LoginComponent/> 
  </div>
  <HeroesComponent/>
  <ProductComponent/>
  <OrderComponent/>
  <TestimoniComponent/>
  <FAQsComponet/>
  <FooterComponent/>
</template>

<script>
import LoginComponent from './LoginComponent.vue';
import HeroesComponent from './HeroesComponent.vue';
import ProductComponent from './ProductsComponent.vue'
import TestimoniComponent from './TestimoniComponent.vue';
import FAQsComponet from './FAQsComponet.vue';
import FooterComponent from './FooterComponet.vue';
import OrderComponent from './OrderComponent.vue';
export default {
  name: 'HelloWorld',
  components: {
    LoginComponent,
    HeroesComponent,
    ProductComponent,
    TestimoniComponent,
    FAQsComponet,
    FooterComponent,
    OrderComponent
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #888888;
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
