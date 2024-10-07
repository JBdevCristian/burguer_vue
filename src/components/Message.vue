<template>
        <div class="mensagem-do-sistema">
            <p>{{ msg }}</p>
        </div>
</template>

<script>
    export default {
        name: "Mensagem",
        props: {
            msg: String
        }
    }
</script>

<style scoped>
    .mensagem-do-sistema {
        color: #004085;
        background-color: #CCE5FF;
        border: 1px solid #B8DAFF;
        border-radius: 5px;
        padding: 10px;
        max-width: 400px;
        margin: 30px auto;
        text-align: center;
    }
</style>