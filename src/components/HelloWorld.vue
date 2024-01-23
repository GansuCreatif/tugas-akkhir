<template>
  <!--<ConditionalComponent/>
  <LoopingComponent/>
  <AtributBandingComponent/>
  <MethodComponent/>-->
  <NavigasiComponent/>
</template>

<script>
import NavigasiComponent from './NavigasiComponent.vue';
//import ConditionalComponent from './ConditionalComponent.vue';
//import LoopingComponent from './LoopingComponent.vue';
//import AtributBandingComponent from './AtributBandingComponent.vue';
//import MethodComponent from './MethodComponent.vue';
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
    //ConditionalComponent,
    //LoopingComponent,
    //AtributBandingComponent,
    //MethodComponent
    NavigasiComponent
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
  color: #42b983;
}
</style>
