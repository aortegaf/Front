<template>
  <div class="CreateAccount">
    <label><input type="radio" name="persona" value="user" data.condition1=true>Usuario</label>
    <label><input type="radio" name="persona" value="owner">Propietario</label>
    
    <div id="container">
      <div v-if="condition1"><CreateUser></CreateUser></div>
      <div v-if="condition2"><CreateOwner></CreateOwner></div>
    </div> 
  </div>
</template>

<script>
import CreateUser from './CreateUser.vue'
import CreateOwner from './CreateOwner.vue'

export default {
  name: 'CreateAccount',
  components: { 
    CreateUser,
    CreateOwner
  },
  data: () => ({
    condition1: false,
    condition2: true
  }),

}
</script>

<style>
</style>
