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
      <section id="producto-datos">
        <h1>Silla de Oficina Ergonomica Negra</h1>
        <h2>166.50 €<span class="iva">Descuento:30%</span></h2>
        <div class="wrapper">
          <button
            class="btn"
            @click="cambiarContador('-1')"
            type="button"
            name="button"
          >
            -
          </button>
          <input class="cantidad" type="text" name="name" :value="contador" />
          <button
            class="btn"
            @click="cambiarContador('1')"
            type="button"
            name="button"
          >
            +
          </button>
        </div>
        <br />
        <button class="boton">
          <span class="material-icons"></span> AÑADIR CARRITO </button>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  Name: 'ProductoDatos',
    data () {
        return {
            contador: 1
        }
    },
    methods: {
        cambiarContador(num) {
            this.contador += +num;
            if (!isNaN(this.contador) && (this.contador < 0)) {
              this.contador = 0
            }
        }
    }
}

</script>


<style scoped >
.container_producto,
div .container_producto {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}

div.precio_descuento {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
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
  /*border: 1px solid #e46a3a;*/
}
section#producto-datos {
  flex: 1 1 18rem;
}
h1 {
  font-size: 2.2rem;
}
h2 {
  font-size:1.7rem;
  color: #1abc9c;
}
span.iva {
  font-size:1rem;
  font-weight: normal;
  color: #282828
}
.wrapper {
  height: 2rem;
  display: flex;
}
.cantidad {
  border: none;
  text-align: center;
  width: 2rem;
  font-size: 1.2rem;
  border: 1px solid #9A9AAC;
}
.btn {
 width: 1.8rem;
}
button:focus, input:focus {
  outline: 0;
}
</style>