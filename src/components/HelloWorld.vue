<template>
  <div class="hello">
    <img alt="Logo" src="./../assets/logo.png">
    <h1>{{ msg }}</h1>
  </div>

  <button class="btn btn-primary">
    We got Bootstrap!
  </button>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
/* ... */
</style>
