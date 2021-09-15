<template>
  <div class="calculator">

    <div class="display">9890898</div>
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

.display{
  /*specify how many column the display takes*/
  grid-column:1/5 ;  /*start at column one and end after column 4*/
  background-color: red;
}


</style>
