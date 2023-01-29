<template>
<section class="section-detail">
  <div class="container">
    <div class="card mb-3">
  <img src="https://img.freepik.com/vector-gratis/error-404-ilustracion-concepto-paisaje_114360-7898.jpg?w=2000" class="card-img-top image" alt="no encontrado">
  <div class="card-body d-flex justify-content-center align-items-center flex-column">
      <h1>Oops!</h1>
      <h2>🌳GardenSHOP🌳</h2>
      <p>No ha encontrado la pagina que estas buscando</p>
  </div>
</div>
  </div>
</section>
</template>

<script>
export default {
  name: 'NotFoundView',
}
</script>

<style scoped>
.section-detail{
   padding: 24px;
  width: 100%;
  height: 100%;
}
.image{
  object-fit: cover;
  height: 500px;
}
</style>