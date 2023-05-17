<script setup>
</script>

<template>
    <div id="jumbo">
        <img src="/vite.svg" class="logo logoVite" alt="Vite logo" />
        <img src="../assets/vue.svg" class="logo logoVue" alt="Vue logo" />
    </div>
    <div id="linkDiv">
        <div id="vite">
            <a href="https://vitejs.dev/">Vai a Vite</a> 
        </div>
        <div id="vue">
            <a href="https://vuejs.org/">Vai a Vue</a> 
        </div>
    </div>
</template>

<style scoped>
    #jumbo {
        top: 0;
        left: 0;
        position: fixed;
        z-index: -1;
        width: 100%;
        height: 100vh;
        background-color: blanchedalmond;
        padding-top: 25vh;
        display: flex;
        justify-content: space-between;
    }
    .logo {
        height: 30em;
    }
    #linkDiv {
        position: absolute;
        top: 50vh;
        left: 50%;
        transform: translate(-50%,-50%);
        font-size: 5rem;
    }
    #vite a:hover,
    #vite a:visited {
        color: black;
    }
    #vue a:hover,
    #vue a:visited {
        color: #fff;
    }
    #vite,
    #vue {
        padding: 15px;
        border-radius: 0.75rem;
        margin-bottom: .3em;
    }
    #vite {
        background: linear-gradient(0.25turn, #54BAFF, #BD34FE);
    }
    #vue {
        color: #fff;
        background: linear-gradient(0.25turn, #35495E, #41B883)
    }
</style>