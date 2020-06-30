<template>
    <section>
    <h1>Es es MI COMPONENTE</h1>
    <p> {{subtitulo}}</p>
    </section>
</template>

<script>
export default {
    name: "miComponente",
    data(){
        return{  
            subtitulo: "este es un subtitulo dentro de la data de miComponente"
         }        
    }
}
</script>