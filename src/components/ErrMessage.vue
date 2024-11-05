<template>
    <div class="mensagem-do-sistema">
        <p>{{ errMsg }}</p>
    </div>
</template>

<script>
export default {
    name: "Mensagem",
    props: {
        errMsg: String
    }
}
</script>

<style scoped>
.mensagem-do-sistema {
    color: #850000;
    background-color: #ffcccc;
    border: 1px solid #ffb8b8;
    border-radius: 5px;
    padding: 10px;
    max-width: 400px;
    margin: 30px auto;
    text-align: center;
}
</style>