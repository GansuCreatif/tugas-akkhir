<template>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 16px 7%;
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
