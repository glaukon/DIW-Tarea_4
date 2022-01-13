<template>
  <div>
    <div class="logo">
      <div class="container">
        <img src="../assets/logo.png" alt="Logo" />
      </div>
    </div>
    <section class="barra_menu">
      <nav class="menu">
        <ul>
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Prueba 1</a></li>
          <li><a href="#">Prueba 2</a></li>
          <li><a href="#">Prueba 3</a></li>
          <li><a href="#">Prueba 4</a></li>
          <li><a href="#">Prueba 5</a></li>
        </ul>
      </nav>
      <div class="login">
        <a href="#">Registro</a>

        <a href="#">Iniciar Sesión</a>
      </div>
    </section>
  </div>
</template>

<script>
</script>


<style>
 .barra_menu{
  /* BARRA MENU COMPLETA*/
  background-color: burlywood;
  text-decoration-line: none;
}


nav ul li{
  /* Menu Navegacion*/
  display: flex; 
  float: left; /* Hacemos que el menu se muestre horizontal */
  list-style-type: none; /* Quita los puntos de las listas */
  justify-content: center;
  
 
  
}

.menu ul li a {
  text-decoration-line: none;
  margin: 10px;
  padding: 8px;
  /*justify-content: center;*/
  
  

}
.login a {
  /* REGISTRO DE USUARIOS*/

  display: flex;
  flex-direction: row;
  text-decoration-line: none;
  margin: 10px;
  padding: 8px;
}
div .login {
  display: flex;
  justify-content: flex-end;



}
a:hover {
  border: 1px solid black;
  border-radius: 20px;
}

img {
  display: flex;
  flex-direction: row;
  height: 50px;
}
</style>
