<template>
   <section>
       <h1>Home</h1>
       <!--<router-link :to="'/equipo/' + id">Equipo Gustavo</router-link> -->
       <router-link :to="{ name: 'equipo', params: {id: id}}">Equipo Gustavo</router-link>
   </section>
</template>

<script>

    export default {
        data(){
            return {
                id:'gustavo'
            }
        }
    }
</script>