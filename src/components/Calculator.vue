<template>
  <div class="calculator">

    <div class="display">0.000668</div>
    <div class="btn">C</div>
    <div class="btn ">+/-</div>
    <div class="btn ">%</div>
    <div class="btn operator">/</div>
    <div class="btn">7</div>
    <div class="btn">8</div>
    <div class="btn">9</div>
    <div class="btn operator">X</div>
    <div class="btn">4</div>
    <div class="btn">5</div>
    <div class="btn">6</div>
    <div class="btn operator">-</div>
    <div class="btn">1</div>
    <div class="btn">2</div>
    <div class="btn">3</div>
    <div class="btn operator ">+</div>
    <div class="btn zero">0</div>
    <div class="btn ">.</div>
    <div class="btn operator">=</div>

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
  margin: 0 auto;
  width: 400px;
  font-size: 40px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}

.display{
  /*specify how many column the display takes*/
  grid-column:1/5 ;  /*start at column one and end after column 4*/
  background-color: #333333;
  color: white;
}
.btn{
  background-color: #F2F2F2;
  border: 1px solid #999;
}

.operator{
  background-color: orange;
  color: #eeeeee;
}

.zero{
  grid-column:1/3 ;
}


</style>
