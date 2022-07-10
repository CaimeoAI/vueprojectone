<template>
    <div class="navbar">
        <ul>
            <li><a href=""><i class="fa-solid fa-house"></i></a></li>
            <li><a href=""><i class="fa-solid fa-chart-line"></i></a></li>
            <li><a href=""><i class="fa-solid fa-cloud-sun"></i></a></li>
            <li><a href=""><i class="fa-regular fa-newspaper"></i></a></li>
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
        position: fixed;
        display: flex;
        justify-content: center;
        flex-direction: column;
        width: 2rem;
        height: 100vh;
        background-color: #E4E6EB;
    }

    ul {
        padding: 0;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
    }

    li {
        margin: 1rem 0;
        list-style-type: none;
    }

    a{
        text-decoration: none;
        color: inherit;
    }
</style>