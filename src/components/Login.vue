<template>
  <form v-on:submit.prevent="Ingresar()">

  <div class="container">
    <label for="user"><b>Usuario</b></label>
    <input type="text" name="user" required v-model="data.user" autocomplete="off">
    <br>
    <label for="password"><b>Contraseña</b></label>
    <input type="password" name="password" required v-model="data.password">
    <br>

    <button type="submit">Ingresar</button>
  </div>


</form> 
</template>

<script>
export default {
  name: 'Login',
  data(){
    return {
      data: {
        user: '',
        password: ''
      }
    }
  },
  methods:{
    Ingresar(){
      alert("Datos recopilados")
      alert(this.data)
    }
  }
}
</script>

<style>
</style>
