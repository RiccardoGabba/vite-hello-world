<template>
 
  <main>
    <div class="scritta">

     <h1>{{ titolo }}</h1>
     <span>{{ nuonaparola }}</span>
    </div>
   </main>
 
 </template>

<script>
  export default{
  name: 'HelloWorld',
  components: {
  },
  data() {
    return {
      titolo: 'Ciccios Move',
      nuonaparola: 'lezzo'
    }
  },
  methods: {

  }
}

</script>



<style scoped>

</style>
