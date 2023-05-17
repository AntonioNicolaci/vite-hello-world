<script setup>
</script>

<template>
    <div id="jumbo">
        <img src="/vite.svg" class="logo" alt="Vite logo" />
        <img src="../assets/vue.svg" class="logo vue" alt="Vue logo" />
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
</style>