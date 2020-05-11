<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <router-link to="/" class="nav-item nav-link">Inicio</router-link> 
                    <router-link to="/about" class="nav-item nav-link">Nosotros</router-link> 
                    <router-link to="/users" class="nav-item nav-link">Usuarios</router-link>
                    <router-link to="/admin" class="nav-item nav-link">Admin</router-link>
                    <!-- <a class="nav-item nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
                    <a class="nav-item nav-link" href="#">Features</a>
                    <a class="nav-item nav-link" href="#">Pricing</a>
                    <a class="nav-item nav-link disabled" href="#">Disabled</a> -->
                </div>
            </div>
        </nav>
        <router-view/>
    </div>
</template>

<script>

export default {
    name: 'Navegador'
}
</script>