<template>
  <v-app>
    <div id="app">
      <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> |
        <router-link to="/personajes">Personajes</router-link>
      </div>
      <router-view/>
    </div>
  </v-app>
</template>

<script>

export default {

}
</script>
<style>

</style>
