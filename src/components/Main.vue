<template>
  <div class="container">
    <div class="bg-comics"></div>
    <div class="comicsbook">
      <div class="text">
        <a href="#" class="text_uppercase btn_singup up">current series</a>
        <div class="ciao"></div>
    <!-- <Maincomicsbook /> -->
        <a href="#" class="text_uppercase btn_singup down">load more</a>
      </div>
    </div>
  </div>
</template>

<script>
// import MainComicsBook from './commons/MainComicsBook.vue';

export default {
  name: 'Main',
  // components: { 
  //   Maincomicsbook 
  //   }
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
  height: 100%;
  width: 100%;
}

.bg-comics{
  background-image: url(../assets/img/jumbotron.jpg);
  height: 350px;
  width: 100%;
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;

}

.comicsbook{
  height: 550px;
}
.text{
  position: relative;

  .btn_singup{
    background-color: $mainColor;
  }
}

.up{
  position: absolute;
  top: -20px;
}
.down{
  position: absolute;
  bottom: 0;
  left: 50%;
  font-size: 12px;
  padding: 10px 50px;
  transform: translate(-50%);
}


.ciao{
  height: 450px;
  width: 100%;
}

</style>
