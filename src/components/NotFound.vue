<template>
    <div>
        <div class="row">
        <div class="col-md-12">
            <h2>Perdón, algo hemos hecho mal, pero esta página no existe</h2>
            <hr>
            <router-link class="btn btn-light-green" :to="{name: 'inicio'}">Volver al Inicio</router-link>
        </div>
    </div>
    </div>
    <div class="container flex flex-col items-center mt-10">
        <h1 class="text-3xl mb-3">Lo sentimos, esta página no existe</h1>
        <router-link class="btn btn-light-green" :to="{ name: 'home' }">Volver al Inicio</router-link>
    </div>
</template>

<script>
export default {};
</script>

<style>

</style>