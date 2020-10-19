<template>
  <div class="Welcome">
    <p>ALECTRION</p>
    <div class="Inicio">
      <button>
        <router-link to='/login' title='Iniciar Sesión'> Iniciar Sesión</router-link>
      </button>
      <button>
        <router-link to='/createaccount' title='Crear Cuenta'>Crear Cuenta</router-link>
      </button>
    </div>
    <footer>Desarrollado por &copy; 2020</footer>
  </div>
</template>

<script>
export default {
  name: 'Welcome'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Orbitron');
.Welcome {
  background:black;
  width: 100%;
  height: 100vh;
  border: 5px solid red;
}
p {
  font-family: Orbitron;
  font-size: 200px;
  text-align: center;
  color: white;
  text-shadow: lightgray 0px 0px 20px;
  vertical-align: middle;
  margin: 0px;
  padding: 0;
  border: 5px solid red;
}
.Inicio {
  justify-content:center;
  margin-left: auto;
  margin-right: auto;
  font-family: Orbitron;
  font-size: 50px;
  color: white;
  background: transparent;
  border: 5px solid red;
}
footer {
  font-family: Orbitron;
  color: white;
  text-align: center;
  border: 5px solid red; 
  bottom: 0;
  text-align: center;
  margin: auto;
  position: fixed;

}
</style>
  