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
          height="100"
          width="100"
        />
        <img
          src="../assets/oficina_3.jpg"
          alt="Silla Oficina"
          height="100"
          width="100"
        />
        <img
          src="../assets/oficina_4.jpg"
          alt="Silla Oficina"
          height="100"
          width="100"
        />
        <img
          src="../assets/oficina_5.jpg"
          alt="Silla Oficina"
          height="100"
          width="100"
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
          <br />
        </div>
        <button class="boton"><span></span> AÑADIR CARRITO</button>
      </section>

      <section class="txt_articulo">
        <hr />
        <h3>Caracteristicas</h3>
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/ZL8bRCjdvR8"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
        <ul>
          <li>
            Dimensiones - Alto: 104,5-113 cm. / Ancho: 63 cm. / Fondo: 46 cm. /
          </li>
          <li>Dimensiones Brazos - Alto: 18-26 cm. /</li>
          <li>Dimensiones Respaldo - Alto: 58 cm. /</li>
          <li>Base giratoria de poliamida negra</li>
          <li>Respaldo de malla negra</li>
          <li>Asiento tapizado en tela negra</li>
          <li>Mecanismo Sincro</li>
          <li>Apoyo lumbar regulable en altura</li>
          <li>Asiento regulable en altura</li>
          <li>Brazos 1D (regulables en altura)</li>
          <li>
            *Fácil montaje (incluye instrucciones. También las puedes encontrar
            aquí)
          </li>
          <li>
            *Los acabados mostrados pueden presentar una ligera variación de
            color/tono respecto a los originales.
          </li>
          <li>GASTOS DE ENVÍO GRATUITOS A LA PENÍNSULA</li>
          <li>Silla Ergonómica nueva para teletrabajar</li>
        </ul>
        
        <hr />
      </section>
    </div>
  </div>
</template>

<script>
export default {
  Name: "ProductoDatos",
  data() {
    return {
      contador: 1,
    };
  },
  methods: {
    cambiarContador(num) {
      this.contador += +num;
      if (!isNaN(this.contador) && this.contador < 0) {
        this.contador = 0;
      }
    },
  },
};
</script>


<style scoped >
div .container_producto {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}

div.descripcion {
  margin: 0px;
  padding: 0px;
  display: flex;
  flex-direction: column;
}
div.precio_descuento {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin: 10px;
}
iframe{
  display:flex;
  margin-left: 24px;
}
.minifotos {
  display: flex;
  flex-direction: row;
  margin: 10px;
}
.minifotos img {
  margin: 10px;
  padding: 10px;
}
hr {
  border: 0px;
  height: 1px;
  background-color: #000000;
}
h1 {
  font-size: 2.2rem;
}
h2 {
  font-size: 1.7rem;
  color: #087e8b;
}
hr {
  border: 0px;
  height: 1px;
  background-color: #000000;
}
span.iva {
  font-size: 1rem;
  font-weight: normal;
  color: #282828;
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
  border: 1px solid #9a9aac;
}
.btn {
  width: 1.8rem;
}
.boton {
  margin-top: 30px;
  margin-bottom: 30px;
  border: 0px;
  width: 180px;
  height: 55px;
  background-color: #087e8b;
  color: white;
}
.boton:hover {
  background-color: #e46a3a;
  color: white;
}
button:focus,
input:focus {
  outline: 0;
}
</style>