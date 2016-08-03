<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="bg-component">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores repudiandae enim at, quidem consequuntur est molestias optio ad unde. Delectus sint minus, omnis est magnam dolorum voluptatum reiciendis fugit reprehenderit?
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      msg: 'Hello World!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: #42b983;
}
.bg-component {
  padding: 50px;
  background: url('../assets/bg_site_pc.jpg') 0 0 no-repeat;
  margin-bottom: 20px;
}
</style>
