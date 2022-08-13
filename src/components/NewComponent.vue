<template>
    <div>
<H1>Este es un componente</H1>
<p> El numero actual es {{ numero }}</p>
<button @click="sumar">Sumar</button>
<button @click="restar">Restar</button>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                numero: 0,
            }
        },
        methods: {
            sumar() {
                this.numero++
            },
            restar() {
                this.numero--
            }
        },
    }
</script>

<style scoped>

</style>