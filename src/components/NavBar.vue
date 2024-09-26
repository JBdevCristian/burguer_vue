<template>
     <div id="nav">
        <router-link to="/" id="logoURL">
            <img :src="logo" :alt="alt" id="logo">
        </router-link>
        <router-link to="/">Home</router-link>
        <router-link to="/pedidos">Pedidos</router-link>
    </div>
</template>

<script>
    export default {
        name: 'Navbar',
        props: ["logo", "alt"]
    }
    
</script>

<style escoped>
    #nav {
        background-color: #222;
        border-bottom: 4px solid #111;
        padding: 15px 40px;
        display: flex;
        justify-content: flex-end;
        align-items: center;
    }

    #nav #logoURL {
        margin: auto;
        margin-left: 0;
    }

    #logo {
        width: 40px;
        height: 40px;
    }

    #nav a {
        color: #FCBA03;
        text-decoration: none;
        margin: 12px;
        transition: 1.2s;
    }

    #nav a:hover {
        color: #fff;
    }

</style>