<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>{{ welcome }}</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: 'Hello Vue!!!',
      welcome: 'Welcome to myBlogs',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  text-align: center;
}
h1 {
  color: #42b983;
}
h2 {
  color: #ddd;
}
</style>
