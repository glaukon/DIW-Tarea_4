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
section{
  background-color: green;
}

nav ul li{
  /* Menu Navegacion*/
  display: flex; 
  float: left; /* Hacemos que el menu se muestre horizontal */
  list-style-type: none; /* Quita los puntos de las listas */
  
  
 
  
}

.menu  ul li a {
  text-decoration-line: none;
  margin: 10px;
  padding: 8px;
  
  

}
.login a {
  /* REGISTRO DE USUARIOS*/


  text-decoration-line: none;
  margin: 10px;
  padding: 8px;
}


div.login {
  display: flex;
 justify-content:flex-end;



}
a:hover {
  margin-block: auto ;
  border: 2px solid white;
  border-radius: 10px;


}

img {
  display: flex;
  flex-direction: row;
  height: 50px;
}
</style>
