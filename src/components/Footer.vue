<template>
  <div class="container">
      <div class="head">
        <div class="text_head">
          <ul>
            <li>
              <img src="../assets/img/buy-comics-digital-comics.png" alt="">
              <a class="text_uppercase text-font" href="#">digital comics</a>
            </li>
            <li>
              <img src="../assets/img/buy-comics-merchandise.png" alt="">
              <a class="text_uppercase text-font" href="#">dc merchandise</a>
            </li>
            <li>
              <img src="../assets/img/buy-comics-subscriptions.png" alt="">
              <a class="text_uppercase text-font" href="#">subscription</a>
            </li>
            <li>
              <img src="../assets/img/buy-comics-shop-locator.png" alt="">
              <a class="text_uppercase text-font" href="#">comic shop locator</a>
            </li>
            <li>
              <img src="../assets/img/buy-dc-power-visa.svg" alt="">
              <a class="text_uppercase text-font" href="#">dc power visa</a>
            </li>

          </ul>
        </div>
      </div>
      <div class="middle">
        <div class="text">
          <nav>
            <ul class="my_d-flex">
              <li>
                <ul>
                  <h3 class="text_uppercase">dc comics</h3>
                  <li>
                    <a href="">Characters</a>
                  </li>
                  <li>
                    <a href="">Comics</a>
                  </li>
                  <li>
                    <a href="">Movies</a>
                  </li>
                  <li>
                    <a href="">TV</a>
                  </li>
                  <li>
                    <a href="">Games</a>
                  </li>
                  <li>
                    <a href="">Videos</a>
                  </li>
                  <li>
                    <a href="">News</a>
                  </li>
                  <li>
                    <h3 class="text_uppercase">shop</h3>
                  </li>
                  <li>
                    <a href="">Shop DC</a>
                  </li>
                  <li>
                    <a href="">Shop DC Collectibles</a>
                  </li>
                </ul>
              </li>
              <li>
                <ul>
                  <h3 class="text_uppercase">dc</h3>
                  <li>
                    <a href="">Terms Of Use</a>
                  </li>
                  <li>
                    <a href="">Privacy policy (New)</a>
                  </li>
                  <li>
                    <a href="">Ad Choices</a>
                  </li>
                  <li>
                    <a href="">Advertising</a>
                  </li>
                  <li>
                    <a href="">Jobs</a>
                  </li>
                  <li>
                    <a href="">Subscriptions</a>
                  </li>
                  <li>
                    <a href="">Talent Workshop</a>
                  </li>
                  <li>
                    <a href="">CPSC Certificates</a>
                  </li>
                  <li>
                    <a href="">Ratings</a>
                  </li>
                  <li>
                    <a href="">Shop Help</a>
                  </li>
                  <li>
                    <a href="">Contact Us</a>
                  </li>
                </ul>
              </li>
              <li>
                <ul>
                  <h3 class="text_uppercase">sities</h3>
                  <li>
                    <a href="">DC</a>
                  </li>
                  <li>
                    <a href="">MAD Magazine</a>
                  </li>
                  <li>
                    <a href="">DC Kids</a>
                  </li>
                  <li>
                    <a href="">DC Universe</a>
                  </li>
                  <li>
                    <a href="">DC Power Visa</a>
                  </li>
                  <li>
                    <a href="">Videos</a>
                  </li>
                  <li>
                    <a href="">News</a>
                  </li>
                </ul>
              </li>
            </ul>
          </nav>        
        </div>
      </div>
      <div class="tail">
        <div class="streak">
            <div class="text">
              <a href="#" class="text_uppercase btn_singup">sing-up now!</a>
              <nav>
                <ul>
                    <li><a href="#" class="text_uppercase">follow us</a></li>
                    <li>
                      <a href="#">
                        <img src="../assets/img/footer-facebook.png" alt="">
                      </a>
                    </li>
                    <li>
                      <a href="#">
                        <img src="../assets/img/footer-twitter.png" alt="">
                      </a>
                    </li>
                    <li>
                      <a href="#">
                        <img src="../assets/img/footer-youtube.png" alt="">
                      </a>
                    </li>
                    <li>
                      <a href="#">
                        <img src="../assets/img/footer-pinterest.png" alt="">
                      </a>
                    </li>
                    <li>
                      <a href="#">
                        <img src="../assets/img/footer-periscope.png" alt="">
                      </a>
                    </li>
                </ul>
              </nav>
            </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../assets/style/Partials/Variables.scss";

//head
.text_head{
  width: 67%;
  margin: 0 auto;
}

.head{
  background-color: #3373e9;
  height: 130px;
  display: flex;
  align-items: center;

  ul{
  list-style-type: none;
  display: flex;
  justify-content: center;
  align-items: center;

  li {
    display: flex;
    align-items: center;
    padding: 0 16px;

      a{
      display: inline-block;
      color: $secondColor;
      padding: 5px 5px;
      text-decoration: none;
      }
  }
}
}



.head img{
  height: 40px;
}

.text-font{
  font-size: 10px;
}


//middle
.middle{
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  height: 350px;

  .text{
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    height: 100%;
    background-position: right center;
  }
  nav{
    padding: 20px 0;
    ul{
      padding: 5px 10px;
      li{
        padding: 3px 0;
        list-style-type: none;
        a{
          font-size: 10px;
          opacity: 0.6;
          color: $secondColor;
          text-decoration: none;
        }
      }
    }
  }
}

h3{
  color: $secondColor;
  padding: 10px 0;
  font-size: 12px;
}

//tail
.streak{
  background-color: $fourthColor;
  display: flex;
}

.tail{

  .text{
    width: 65%;
    margin: 0 auto;  
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  nav{
    
    ul{
      list-style-type: none;
      display: flex;
      justify-content: center;
      align-items: center;

      li{
        display: flex;
        align-items: center;
        padding: 0 5px;

        a{
        color: $mainColor;
        display: inline-block;
        padding: 5px 5px;
        text-decoration: none;

          img{
          height: 30px;
          }
        }
      }
    }
  }
}   

</style>
