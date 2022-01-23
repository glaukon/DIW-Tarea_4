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
        <img
          src="../assets/oficina_2.jpg"
          alt="Silla Oficina"
          height="150"
          width="150"
        />
        <img
          src="../assets/oficina_3.jpg"
          alt="Silla Oficina"
          height="150"
          width="150"
        />
        <img
          src="../assets/oficina_4.jpg"
          alt="Silla Oficina"
          height="150"
          width="150"
        />
      </div>
    </div>
    <div class="descripcion">
      <div class="datos_producto">
        <div>
          <h1>Silla de Oficina Ergonomica Negra</h1>
        </div>
        <div class="precio_descuento">
          <div><label>Precio</label>
          <label>Descuento</label></div>
          <div><strong>166.50 €</strong>
          <strong>30%</strong></div>
        </div>
        <div class="btncomprar">
          <input class="cantidad" type="submit" name="name" value="Comprar" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped >
.container_producto,
div .container_producto {
  border: solid 1px #e46a3a;
  display: flex;
  flex-direction: row;
  justify-content: space-between;

}

.foto {
  border: solid 1px #e46a3a;

  /*display: flex;
  flex-direction: row;
  justify-content: center;
  background-color: aqua;*/
}

div.precio_descuento {
  display: flex;
  flex-direction: column;
  justify-content:space-between;
  /*align-items: center;*/
  margin: 10px;
}

.minifotos {
  display: flex;
  flex-direction: row;
  margin: 10px;
}
.minifotos img {
  margin: 10px;
  padding: 10px;
  border: 1px solid #e46a3a;
}
</style>