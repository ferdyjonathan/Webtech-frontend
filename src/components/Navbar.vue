<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">
      <router-link class="nav-link" to="/"><img src="@/assets/Logo_Laundy.png" width="60" height="45" class="d-inline-block align-top" alt=""></router-link>
    </a>
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <router-link class="nav-link" to="/">Dashboard</router-link>
          <router-link class="nav-link" to="/employee">Employee</router-link>
<!--          <router-link class="nav-link" to="/bestellungs">Bestellung</router-link>-->
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>

</style>
