<template>
<div class="headertop">
  <header>
  
    <nav class="navbar navbar-expand-lg navbar-dark bg-saleemary">
      <img id="img" src="../assets/header.png">
      <h1>Trocomania</h1>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="/">Accueil</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="/#/products/">Produits</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="/#/signin/">Inscription</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="/#/connexion/">Connexion</a>
          </li>
        </ul>
        <ul class="navbar-nav nav-flex-icons">
          <li class="nav-item">
            <a class="nav-link"><i class="fab fa-facebook-f"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link"><i class="fab fa-twitter"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link"><i class="fab fa-instagram"></i></a>
          </li>
        </ul>
      </div>
    </nav>
</header>
  </div>
</template>

<script>
export default {
  name: 'headertop'
  
}
</script>

<style lang="scss" scoped>

#img{
  width: 5%;
  @media screen and (min-width: 300px) and (max-width: 500px){
    width: 12.5%;
  }
}

h1{
  color: #FFF;
  position: relative;  
}

// .navbar{
//   background-color: pink;
// }
</style>

