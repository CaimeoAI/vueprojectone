<template>
    <section>
        <div class="container title-container">
            <h1 class="lead">My first Vue.js Project</h1>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'LandingPage'
    }
</script>

<style scoped>
    section {
        width: 100vw;
        height: calc(100vh - 2rem);
    }

    .title-container {
        width: 100%;
    }

    h1 {
        padding-top: 2rem;
        text-align: center;
        font-weight: bold;
        text-transform: uppercase;
    }
</style>