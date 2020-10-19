<template>
  <div class="CreateUser">
    <b>Nombre</b>
    <br>
    <input type="text" name="name">
    <br>
    <b>Correo</b>
    <br>
    <input type="text" name="email">
    <br>
    <b>Usuario</b>
    <br>
    <input type="text" name="user">
    <br>
    <b>Contraseña</b>
    <br>
    <input type="text" name="password">
    <br>
    <button type="submit">Guardar</button>
  </div>
</template>

<script>
export default {
  name: 'CreateUser'
}
</script>

<style>
</style>
