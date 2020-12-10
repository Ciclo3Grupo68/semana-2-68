<template>
    <nav class="navbar navbar-expand-md sticky-top navbar-dark bg-dark">
            <div class="container">
               <a href="" class="navbar-brand">
                Cloud Computing
               </a>
               <button button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#firstnavbar">
                <span class="navbar-toggler-icon"></span>
               </button>

               <div class="navbar-collapse" id="firstnavbar">
                    <ul class="navbar-nav ml-auto nav nav-pills">
                        <li class="nav-item"><a class="nav-link" id="tab-1" data-toggle="tab" role="tab" href="#">Inicio</a></li>
                        <li class="nav-item"><a class="nav-link" id="tab-2" data-toggle="tab" role="tab" href="#">Servicios</a></li>
                        <li class="nav-item"><a class="nav-link" id="tab-3" data-toggle="tab" role="tab" href="#">Noticias</a></li>
                        <li class="nav-item"><a class="nav-link" id="tab-4" data-toggle="tab" role="tab" href="#">Miembros</a></li>
                    </ul>
                </div>
            </div>
        </nav>
</template>

<script>
    export default {
        name: "TopMenu",
    }
</script>

<style>

</style>