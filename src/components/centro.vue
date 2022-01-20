<template>
  <div class="container_producto">
    <div class="foto">
      <img
        src="../assets/oficina_1.jpg"
        alt="Silla Oficina"
        height="540"
        width="320"
      />
      <div class="minifotos">
        <img src="../assets/oficina_2.jpg"
        alt="Silla Oficina"
        height="150"
        width="150">
         <img src="../assets/oficina_3.jpg"
        alt="Silla Oficina"
        height="150"
        width="150">
         <img src="../assets/oficina_4.jpg"
        alt="Silla Oficina"
        height="150"
        width="150">
      </div>
    </div>

    <div class="descripcion">
      <h2>Descripcion Articulo</h2>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped >
.container_producto,
div .container_producto {
  border: solid 1px #E46A3A;;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 66px;
  width: auto;
}

.foto {
  border: solid 1px #E46A3A;
  
  /*display: flex;
  flex-direction: row;
  justify-content: center;
  background-color: aqua;*/
}
.descripcion {
  
  /*display: flex;*/
  /*flex-direction: row;*/
  /*justify-content: right;*/
  /*background-color: #6e8894;*/

}
.minifotos{
  display: flex;
  flex-direction: row;
  margin: 10px;
}
.minifotos img{
  margin: 10px;
  padding: 10px;
  border: 1px solid #E46A3A;
}
</style>