<template>
    <div class="navbar">
        <ul>
            <li><a href="">Home</a></li>
            <li><a href="">Link 1</a></li>
            <li><a href="">Link 2</a></li>
            <li><a href="">Link 3</a></li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: 'NavBar'
    }
</script>

<style scoped>
    .navbar {
        display: flex;
        justify-content: center;
        width: 100vw;
        height: 2rem;
        background-color: steelblue;
    }

    ul {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    li {
        margin: 0px 1rem;
        list-style-type: none;
    }

    a{
        text-decoration: none;
        color: inherit;
    }
</style>