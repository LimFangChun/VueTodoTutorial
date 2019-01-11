<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>{{ var2 }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    var2: String
  }
}
</script>

<style>

</style>
