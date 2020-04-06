<template>
    <div class="container">
        <!-- Example row of columns -->
        <div class="row">
          <div class="col-md-4" v-for="name in data" :key="name.id">
            <h2>{{ name.head }}</h2>
              <p>{{ name.article }}</p>
            <p><a class="btn btn-secondary" href="#" role="button">Прочитать полностью »</a></p>
          </div>
        </div>
        <hr>
      </div>
</template>

<script>
    export default {
        name: "SmallNews",
        props:['data']
    }
</script>

<style scoped>

</style>