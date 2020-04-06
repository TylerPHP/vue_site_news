<template>
    <div class="jumbotron">
        <div class="container" v-for="name in data" :key="name.id">
          <h1 class="display-3">{{ name.head }}</h1>
          <p>{{ name.article }}</p>
          <p><a class="btn btn-primary btn-lg" href="#" role="button">Прочитать полностью »</a></p>
        </div>
      </div>
</template>

<script>
    export default {
        name: "NewsArea",
        props: ['data']
    }
</script>

<style scoped>

</style>