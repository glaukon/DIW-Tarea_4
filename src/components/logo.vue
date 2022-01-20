<template>
  <div class="logo">
    <div class="img">
      <img src="../assets/logo.png" alt="Logo" />
    </div>
  </div>
  <section class="barra_menu">
    <nav class="menu">
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Sillas Oficina</a></li>
        <li><a href="#">Sillas Ergonomicas</a></li>
        <li><a href="#">Sillas Giratorias</a></li>
        <li><a href="#">Sillas Domesticas</a></li>
      </ul>
      <div class="login">
        <ul>
          <li><a href="#">Registro</a></li>
          <li><a href="#">Iniciar Sesión</a></li>
        </ul>
      </div>
    </nav>
  </section>
</template>

<script>
</script>


<style scoped>


*{
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  color: #E46A3A;
}
.barra_menu nav {
 
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  height: 90px;
  background-color: #087E8B;
  
  font-weight: bold;
  font-family: Georgia, 'Times New Roman', Times, serif;
  
}
div .login{
  
  display: flex;
  flex-direction: row;
  float: right; /* Hacemos que el menu se muestre horizontal */
  list-style-type: none; /* Quita los puntos de las listas */
  width: auto;
  height: auto;
  margin-left: auto;
  
  
}



nav ul li {
  /* Menu Navegacion*/
  float: left; /* Hacemos que el menu se muestre horizontal */
  list-style-type: none; /* Quita los puntos de las listas */

  
}

.menu ul li a {
  text-decoration-line: none;
  margin: 10px;
  margin-left: 0px;
  margin-right: 0px;
  padding: 8px;
  font-size: large;
  
}
a:hover{

 /* border: solid 2px #E46A3A;
  border-radius: 10px;*/
  /*background: #E46A3A;*/
  color: white;
}


img {
  display: flex;
  flex-direction: row;
  height: 65px;
}
</style>
