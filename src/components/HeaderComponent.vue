<template>
  <header>

    <div class="up-menu">
      <div class="container d-flex justify-content-between ">
        <!-- social -->
        <div class="social">
          <a href="#">
            <i class="fa-brands fa-facebook-f"></i>
          </a>
          <a href="#">
            <i class="fa-brands fa-twitter"></i>
          </a>
          <a href="#">
            <i class="fa-brands fa-instagram"></i>
          </a>
          <a href="#">
            <i class="fa-brands fa-youtube"></i>
          </a>
        </div>  
        <!-- menu-account -->
        <div class="menu-tendina">
          <nav>
            <ul>
              <li>
                Shopping Cart
              </li>
              <li>
                <span>My Account  </span><i class="fa-solid fa-angle-down"></i>
              </li>
              <li class="li-cart">
                <i class="fa-solid fa-cart-shopping"></i> <span> Cart  </span> <i class="fa-solid fa-angle-down"></i>
              </li>
            </ul>
          </nav>
         
        </div>
      </div>
    </div>

    <!-- down-menu -->
    <div class="down-menu">
      <div class="container d-flex justify-content-between">
        <div class="logo">
          <img src="../assets/img/images/classic_shop_logo2x.png" alt="logo">
        </div>

        <div class="menu-principale">
          <nav>
            <ul>
              <li>
                <span>Home  </span><i class="fa-solid fa-angle-down"></i>
              </li>
              <li>
                <span>Shop  </span><i class="fa-solid fa-angle-down"></i>
              </li>
              <li>
                <span>Products  </span><i class="fa-solid fa-angle-down"></i>
              </li>
              <li>
                <span>Categories  </span><i class="fa-solid fa-angle-down"></i>
              </li>
              <li>
                <span>News  </span>
              </li>
              <li>
                <span>Elements  </span><i class="fa-solid fa-angle-down"></i>
              </li>
              <li class="li-btn">
                <button type="button" class="btn btn-primary cg-btn"> SHOP NOW!</button>
              </li>
              <li class="li-search">
                <i class="fa-solid fa-magnifying-glass"></i>
              </li>
            </ul>
              
          </nav>
        </div>
        

        
      </div>
    </div>

  </header>
</template>

<script>
export default {
name: "HeaderComponent",

}
</script>

<style lang="scss" scoped>
@import "../assets/style/_general.scss";

header{
  .up-menu{
    color:rgb(107, 106, 107);
    border-bottom: 1px solid rgb(107, 106, 107);
    height: 50px;

  }

  .social{
    .fa-brands{
      color:rgb(107, 106, 107);
      font-size: 15px;
      padding: 10px;
      height: 50px;
    }
  }
  .menu-tendina{
    ul li{
      display: inline-block;
      height: 50px;
      padding: 0 20px 0 20px;
      border-right:1px solid rgb(107, 106, 107) ;
      line-height: 50px;
        &:hover{
        cursor: pointer;
      }

    }
    .li-cart{
      padding: 0 80px 0 80px;
    }
    .fa-cart-shopping{
      color: black;
    }
  }

  }

  .down-menu{
    color:rgb(107, 106, 107);
    .logo{
      width: 200px;
      padding:20px 15px 20px 15px;
    }
     ul li{
      display: inline-block;
      height: 90px;
      padding: 0 10px 0 10px;
      border-top: 2px solid white;
      line-height: 100px;
        &:hover{
        cursor: pointer;
        border-top: 2px solid rgb(66, 126, 213);
        color:rgb(66, 126, 213)
      }
     }
      .li-btn:hover{
        border-top: 2px solid white;
      }
      .li-search:hover{
        border-top: 2px solid white;
      }
    .cg-btn{
      border-radius: 20px !important;
      padding: 5px 20px 5px 20px;
      margin-right: 6px;
      font-size: 15px;
    }

  }




</style>