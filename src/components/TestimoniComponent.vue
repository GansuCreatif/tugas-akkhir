<template>
<section id="testimoni">
      <center><h2>Testimoni</h2></center>
    <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
                <div class="container">
                    <div class="row">
                        <div class="col-4">
                            <img src="../assets/avatar.png" class="bd-placeholder-img rounded-circle" width="100" height="100"/>

                            <h2>John Doe</h2>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure recusandae ullam provident, nulla laudantium fugit quisquam quo velit assumenda id nemo. Quaerat ad sint tempora facere omnis voluptatibus cumque fuga.</p>
                            <div>
                                <b-form-rating v-model="value" variant="warning" class="mb-2">
                                    <p class="mt-2">Rating: {{ value }}/5</p>
                                </b-form-rating>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <img src="../assets/avatar.png" class="bd-placeholder-img rounded-circle" width="100" height="100"/>

                            <h2>John Doe</h2>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure recusandae ullam provident, nulla laudantium fugit quisquam quo velit assumenda id nemo. Quaerat ad sint tempora facere omnis voluptatibus cumque fuga.</p>
                            <div>
                                <b-form-rating v-model="value" variant="warning" class="mb-2"></b-form-rating>
                                <p class="mt-2">Rating: {{ value }}/5</p>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <img src="../assets/avatar.png" class="bd-placeholder-img rounded-circle" width="100" height="100"/>

                            <h2>John Doe</h2>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure recusandae ullam provident, nulla laudantium fugit quisquam quo velit assumenda id nemo. Quaerat ad sint tempora facere omnis voluptatibus cumque fuga.</p>
                            <div>
                                <b-form-rating v-model="value" variant="warning" class="mb-2"></b-form-rating>
                                <p class="mt-2">Rating: {{ value }}/5</p>
                             </div>
                        </div>
                    </div>
                </div>
          </div>
          <div class="carousel-item">
            <div class="container">
                    <div class="row">
                        <div class="col-lg-4">
                            <img src="../assets/avatar.png" class="bd-placeholder-img rounded-circle" width="100" height="100"/>

                            <h2>John Doe</h2>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure recusandae ullam provident, nulla laudantium fugit quisquam quo velit assumenda id nemo. Quaerat ad sint tempora facere omnis voluptatibus cumque fuga.</p>
                            <div>
                                <b-form-rating v-model="value" variant="warning" class="mb-2"></b-form-rating>
                                <p class="mt-2">Rating: {{ value }}/5</p>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <img src="../assets/avatar.png" class="bd-placeholder-img rounded-circle" width="100" height="100"/>

                            <h2>John Doe</h2>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure recusandae ullam provident, nulla laudantium fugit quisquam quo velit assumenda id nemo. Quaerat ad sint tempora facere omnis voluptatibus cumque fuga.</p>
                            <div>
                                <b-form-rating v-model="value" variant="warning" class="mb-2"></b-form-rating>
                                <p class="mt-2">Rating: {{ value }}/5</p>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <img src="../assets/avatar.png" class="bd-placeholder-img rounded-circle" width="100" height="100"/>

                            <h2>John Doe</h2>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure recusandae ullam provident, nulla laudantium fugit quisquam quo velit assumenda id nemo. Quaerat ad sint tempora facere omnis voluptatibus cumque fuga.</p>
                            <div>
                                <b-form-rating v-model="value" variant="warning" class="mb-2"></b-form-rating>
                                <p class="mt-2">Rating: {{ value }}/5</p>
                            </div>
                        </div>
                    </div>
                </div>
          </div>
          <div class="carousel-item">
            <div class="container">
                    <div class="row">
                        <div class="col-lg-4">
                            <img src="../assets/avatar.png" class="bd-placeholder-img rounded-circle" width="100" height="100"/>

                            <h2>John Doe</h2>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure recusandae ullam provident, nulla laudantium fugit quisquam quo velit assumenda id nemo. Quaerat ad sint tempora facere omnis voluptatibus cumque fuga.</p>
                            <div>
                                <b-form-rating v-model="value" variant="warning" class="mb-2"></b-form-rating>
                                <p class="mt-2">Rating: {{ value }}/5</p>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <img src="../assets/avatar.png" class="bd-placeholder-img rounded-circle" width="100" height="100"/>

                            <h2>John Doe</h2>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure recusandae ullam provident, nulla laudantium fugit quisquam quo velit assumenda id nemo. Quaerat ad sint tempora facere omnis voluptatibus cumque fuga.</p>
                            <div>
                                <b-form-rating v-model="value" variant="warning" class="mb-2"></b-form-rating>
                                <p class="mt-2">Rating: {{ value }}/5</p>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <img src="../assets/avatar.png" class="bd-placeholder-img rounded-circle" width="100" height="100"/>

                            <h2>John Doe</h2>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure recusandae ullam provident, nulla laudantium fugit quisquam quo velit assumenda id nemo. Quaerat ad sint tempora facere omnis voluptatibus cumque fuga.</p>
                            <div>
                                <b-form-rating v-model="value" variant="warning" class="mb-2"></b-form-rating>
                                <p class="mt-2">Rating: {{ value }}/5</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>

            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>
</section>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@1,700&family=Oswald:wght@200;700&display=swap');
#testimoni{
 background-color: #d0d0d0;
 margin-bottom: 40px;
    h2{
      font-size: 80px;
      color: #050505;
      font-family: 'Chakra Petch', sans-serif;
      font-weight: bold;
  
    }
    
}
</style>
<script>
 export default{
        name: 'TestimoniComponent',
        data() {
            return {
                value: 5
            };
        }
    }
</script>