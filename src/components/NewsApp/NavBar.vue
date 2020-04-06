<template>
    <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">

        <div class="collapse navbar-collapse" id="navbarsExampleDefault">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#">Главная</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Новости сегодня</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Популярное</a>
                </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" v-model="search" type="text" placeholder="поиск..." aria-label="Search">
                <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Поиск</button>
            </form>
        </div>
    </nav>
</template>

<script>

    export default {
        name: "NavBar",
        props: ['search'],
        methods:{

        }
    }
</script>

<style scoped>

</style>