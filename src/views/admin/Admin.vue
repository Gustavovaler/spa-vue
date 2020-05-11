<template>
    <div class="container">
        <div class="container">
            <div class="wrapper mt-5">
                <ul>
                    <li><router-link to="/admin/crear_usuario" class="btn btn-primary btn-block mt-2">Crear Usuario</router-link></li>
                    <li><router-link to="/admin/crear_usuario" class="btn btn-warning btn-block mt-2">Editar Usuario</router-link></li>
                     <li><router-link to="/admin/crear_usuario" class="btn btn-danger btn-block mt-2">Eliminar Usuario</router-link></li>
                </ul>
            </div>
        </div>
        
    </div>
</template>

<script>

export default {
    components:{
      
    }
    
}
</script>

<style  scoped>
.wrapper{
    margin-top: 150px;
    padding: 15px;
    width: 50%;
    margin: auto;
}
</style>