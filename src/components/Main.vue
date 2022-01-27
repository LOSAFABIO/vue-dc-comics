<template>
  <div class="container">
    <div class="text">
      <div class="streak">
         <span> --> Content goes here </span>
      </div> 
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../assets/style/Partials/Variables.scss";

.container{
  background-color: $thirdColor;
}

.streak{
  color: $secondColor;
  display: flex;
  align-items: center;
}

</style>
