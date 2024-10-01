<script setup>

</script>

<template>
  <div style="padding: 16px;">
    <div class="encabezado">
      <div style="display: flex;">
        <div class="bolita"></div>
        <div>Libro Colorear</div>
      </div>
      <div>about</div>
    </div>
    <div>
      <h1>Titulo E1</h1>
      <button class="boton" @click="$router.push('/book')">ir al libro</button>
    </div>
    <div class="imagen-container">
      <img src="@/assets/BUNBUN.png" alt="">
    </div>
  </div>
  <!-- <div> -->
  <!--   <h1>Libro Colorear</h1> -->
  <!--   <button @click="$router.push('/book')">ir al libro</button> -->
  <!-- </div> -->
</template>

<style scoped>
.encabezado {
  display: flex;
  justify-content: space-between;
}

.bolita {
  width: 32px;
  height: 32px;
  background-color: blue;
  margin-right: 8px;
  border-radius: 50%;
}
.imagen-container {
  display: flex;
  justify-content: center;

}
</style>
