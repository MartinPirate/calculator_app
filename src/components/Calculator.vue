<template>
  <div class="calculator">

    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>

  </div>

</template>

<script>
export default {
  name: 'Calculator',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.calculator{
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}

</style>
