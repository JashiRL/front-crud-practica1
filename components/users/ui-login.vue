<template>
  <v-card width="400" heigth="400" color="cyan lighten-5">
    <v-card-title> Welcome</v-card-title>
    <v-card-text>
      <v-form v-model="valid">
        <v-text-field v-model="usuario" type="text" placeholder="Escribe tu usuario" label="Usuario" />
        <v-text-field v-model="password" type="password" placeholder="Escribe la contraseña" label="Password" />
      </v-form>
    </v-card-text>
    <v-card-actions>
      <v-btn elevation="0" color="cyan lighten-5" @click="loginUser">
        <v-icon color="blue lighten-4">
          mdi-
        </v-icon>
        Login
      </v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  data () {
    return {
      valid: false,
      usuario: '',
      password: ''
    }
  },
  methods: {
    loginUser () {
      // eslint-disable-next-line no-console
      console.log('Press de Button')
    }
  }
}
</script>

<style>

</style>
