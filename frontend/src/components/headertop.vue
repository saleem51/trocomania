<template>
  <div class="header">
    <nav class="navbar navbar-expand-lg navbar-dark bg-saleemary">
      <img id="img" src="../assets/header2.png">
      <h1 id="title" class="navbar-brand" href="#">Trocomania</h1>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" id="accueil" href="#">Accueil<span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#">Produits</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link " href="#" tabindex="-1" aria-disabled="false">Annonces</a>
            </li>
            <li class="nav-item active dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Espace Adhérent
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">Inscription</a>
                <a class="dropdown-item" href="#">Connexion</a>
                <!--<div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Something else here</a>-->
              </div>
            </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'headertop'
  
}
</script>

<style lang="scss" scoped>
  
#title{
  font-size: 2.5em;
}

.nav-link{
  margin-top: 20px;
}
#accueil{
  margin-left: 200px;
  @media screen and (min-width: 300px) and (max-width: 992px){
    margin-left: 0px;
  }
}
 
#img{
  width: 5%;
  @media screen and (min-width: 300px) and (max-width: 500px){
    width: 12.5%;
  }
}

.dropdown-item{
  &:hover{
    background-color: #35796a;
    color: #FFF;
  }
}
</style>

