<template>
  <div class="container_pie">
    <div class="ubicacion">
      <span>Ubicacion</span>
      <hr />
      <ul>
        <li>Calle Sin nombre, 2</li>
        <li>Murcia</li>
        <li>30012</li>
      </ul>
    </div>
    <div class="contacto">
      <span>Contacto</span>
      <hr />
      <ul>
        <li>Telefono: 968 123 654</li>
        <li>Email: tienda@sillas.com</li>
        <li>Movil: 666 123 321</li>
      </ul>
    </div>
    <div class="rrss">
      <span>Redes Sociales</span>
      <hr />
      <ul>
        <li>Facebook</li>
        <li>Twitter</li>
        <li>Instagram</li>
      </ul>
    </div>
    <div class="horario">
      <span>Horario Murcia</span>
      <hr />
      <p>
        Lunes a Viernes de 10:00 a 14:00h y de 17:00 a 20:00h. Sábados de 10:00
        a 13:30.
      </p>
      <span>Horario Cartagena</span>
      <p>
        Lunes a Viernes de 10:00 a 14:00h y de 17:00 a 20:00h. Sábados de 09:00
        a 14:00. Domingos de 12: a 16:00.
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container_pie {
  margin: 8px;
  padding: 10px;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
  font-weight: 900;
  width: 100%;
  height: 250px;
  background-color: #03343a;
  color: white;
}
.ubicacion ul,
.contacto ul,
.rrss ul,
.horario p {
  list-style: none;
  text-decoration-line: none;
  font-weight: lighter;
}
span:hover {
  color: #e46a3a;
}


</style>