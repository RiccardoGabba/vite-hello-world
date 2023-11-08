<template>
  <HelloWorld/>
  

</template>

<script>
import HelloWorld from './components/HelloWorld.vue';


export default {
  name: 'App',
  components: {
    HelloWorld,
   
  },
  data() {
    return {
    }
  },
}
</script>

<style lang="css">
:root {
  font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.5;
  font-weight: 400;

  color-scheme: light dark;
  color: rgba(255, 255, 255, 0.87);
  background-color: #242424;
}

.scritta {
  margin: 0;
  text-align: center;
  min-width: 320px;
  min-height: 100vh;
}

 h1{
  font-size: 3.2em;
  line-height: 1.1;
}


  </style>
