<template>
  <nav>
    <NavBar />
  </nav>
  <header class="m-4 p-3">
    <h1 class="text-center">{{ message }} a Inicio </h1>
  </header>
  <div class="d-flex bd-highlight justify-content-center align-items-center">
    <div class="p-2 flex-fill bd-highlight">
      <img src="../assets/img1.svg" class="col-md-6 float-md-end mb-3 ms-md-3 w-100" alt="banner con una chica andando">
    </div>
    <div class="p-2 flex-fill bd-highlight">
      <!-- Botones -->
  <div class="d-grid gap-3">
    <div class="d-grid gap-2 col-6 mx-auto">

      <router-link to="/clientes" class="navbar-brand">
        <button type="button" class="btn btn-primary btn-lg m-2 p-2 w-100">
        Gestión Cliente
        </button>
      </router-link>
      <router-link to="/tareas" class="navbar-brand">
        <button type="button" class="btn btn-primary btn-lg m-2 p-2 w-100">
        Gestión Tareas
        </button>
      </router-link>
      <router-link to="/articulos" class="navbar-brand">
          <button type="button" class="btn btn-primary btn-lg m-2 p-2 w-100">
          Gestión Articulós
          </button>
        </router-link>
        <router-link to="/viajes" class="navbar-brand">
          <button type="button" class="btn btn-primary btn-lg m-2 p-2 w-100">
          Gestion Viajes
          </button>
        </router-link>  
    </div>
  </div>
  <!-- End of Buttons -->

  </div>
</div>

</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  name: "PaginaInicio",
  components: {
    NavBar,
  },
  data() {
    return {
      message: "Bienvenido",
    };
  },
  mounted() {
    console.log("Componente PaginaInicio.vue cargado");
  },
};
</script>

<style>
</style>