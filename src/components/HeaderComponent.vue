<template>
  <header>

    <div class="up-menu">
      <div class="container d-flex justify-content-between ">
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

        <div class="nav-account cg-nav-account">
          <nav class="navbar navbar-expand-lg navbar-light bg-light">
          <div class="container-fluid">
         
          <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav">
              <li class="nav-item shopping-cart">
                <a class="nav-link" href="#">Shopping Cart</a>
              </li>
              <li class="nav-item dropdown my-account">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  My Account
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
              <li class="nav-item dropdown cart">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  <i class="fa-solid fa-cart-shopping"></i> 
                  <span>CART</span> 
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
        </nav>
        </div>
      </div>
    </div>
    <div class="down-menu debug h100">down-menu
      <div class="container d-flex justify-content-between debug">
        <div class="logo debug">logo</div>
        <div class="menu-tendina debug">menu a tendina bootstrap</div>
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
    border-bottom: 1px solid rgb(107, 106, 107);
  }

  .social{
    color:rgb(107, 106, 107);
    .fa-brands{
      color:rgb(107, 106, 107);
      font-size: 15px;
      padding: 10px;
    }
  }
  .cg-nav-account{
    ul li{
      height: 100%;
    }
    .shopping-cart, .my-account{
      border-right: 1px solid rgb(107, 106, 107);
      padding: 0 15px;
    }
    .cart{
      padding: 0 30px 0 30px;
      background-color: rgb(250, 250, 250);
      .fa-cart-shopping{
        padding-right: 20px;
        color: black;
      }
    }

  }

}

</style>