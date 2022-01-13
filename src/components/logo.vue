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
        <a href="#">Registrate</a>
        <a href="#">Iniciar Sesión</a>
      </div>
    </section>
  </div>
</template>

<script>
</script>


<style>
.barra_menu {
  /* BARRA MENU COMPLETA*/
  background-color: aquamarine;
  text-decoration-line: none;
  
  
  
}
.menu ul li{
  /* Menu Navegacion*/
  float: left; /* Hacemos que el menu se muestre horizontal */
  
  
  list-style-type: none; /* Quita los puntos de las listas */
   
}

.menu ul li a {
  
  text-decoration-line: none;
}
.login a {
  /* REGISTRO DE USUARIOS*/
  
  display: flex;
  flex-direction: row;
  text-decoration-line: none;
   
}
div .login{
  display: flex;
 justify-content: flex-end; 
}


img {
  display: flex;
  flex-direction: row;
  height: 50px;
}
</style>
