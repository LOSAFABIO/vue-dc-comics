<template>
  <div class="container">
    <div class="text">
      <div class="streak">
       <img src="../assets/img/dc-logo.png" alt="">
       <nav>
        <ul>
            <li><a class="text_uppercase">characters</a></li>
            <li class="active"><a class="text_uppercase active">comics</a></li>
            <li><a class="text_uppercase">movies</a></li>
            <li><a class="text_uppercase">tv</a></li>
            <li><a class="text_uppercase">games</a></li>
            <li><a class="text_uppercase">collectibles</a></li>
            <li><a class="text_uppercase">videos</a></li>
            <li><a class="text_uppercase">fans</a></li>
            <li><a class="text_uppercase">news</a></li>
            <li><a class="text_uppercase">shop</a></li>
        </ul>
       </nav>
      </div> 
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../assets/style/Partials/Variables.scss";

.streak{
  display: flex;
  justify-content: space-between;
  align-items: center;
}

img{
  height: 60px;
}

ul{
  list-style-type: none;
  display: flex;
  justify-content: center;

  li {
      padding: 30px 0;
      &.active{
        border-bottom: solid 3px $mainColor;
      }

    a{
      display: inline-block;
      color: #000;
      padding: 10px 15px;
      text-decoration: none;

      &.active, &:hover{
        color: $mainColor;
      }
    }
  }
}

</style>
