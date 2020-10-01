<template>

 <nav class="navbar navbar-expand-lg navbar-dark bg-saleemary">
      <img id="img" src="../assets/header2.png">
      <h1 id="title" class="navbar-brand" href="#">Trocomania</h1>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <router-link id="home" to="/">Accueil</router-link> 
            </li>
            <li class="nav-item active">
              <router-link id="prod" to="/products">Produits</router-link> 
            </li>
            <li class="nav-item active">
               <router-link id="Annonces" to="/annonces">Annonces</router-link> 
            </li>
            <li class="nav-item active dropdown">
              <router-link to="/" class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Espace Adhérent
              </router-link>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <router-link id="signin" to="/signin">inscription</router-link> 
                 <div class="dropdown-divider"></div>
                <router-link id="signup" to="/connexion">connexion</router-link> 
                <!--<div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Something else here</a>-->
              </div>
            </li>
        </ul>
      </div>
    </nav>

    <!--<div class="container">
        <h1 class="my-4">Welcome to Modern Business</h1>
            <div class="row">
                <div class="col-lg-4 mb-4">
                    <div class="card h-100">
                    <h4 class="card-header">Card Title</h4>
                    <div class="card-body">
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente esse necessitatibus neque.</p>
                    </div>
                    <div class="card-footer">
                        <a href="#" class="btn btn-primary">Learn More</a>
                    </div>
                    </div>
                </div>
                <div class="col-lg-4 mb-4">
                    <div class="card h-100">
                    <h4 class="card-header">Card Title</h4>
                    <div class="card-body">
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis ipsam eos, nam perspiciatis natus commodi similique totam consectetur praesentium molestiae atque exercitationem ut consequuntur, sed eveniet, magni nostrum sint fuga.</p>
                    </div>
                    <div class="card-footer">
                        <a href="#" class="btn btn-primary">Learn More</a>
                    </div>
                    </div>
                </div>
                <div class="col-lg-4 mb-4">
                    <div class="card h-100">
                    <h4 class="card-header">Card Title</h4>
                    <div class="card-body">
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente esse necessitatibus neque.</p>
                    </div>
                    <div class="card-footer">
                        <a href="#" class="btn btn-primary">Learn More</a>
                    </div>
                    </div>
                </div>
                </div>
                <h2>Portfolio Heading</h2>
                <div class="row">
                <div class="col-lg-4 col-sm-6 portfolio-item">
                    <div class="card h-100">
                    <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
                    <div class="card-body">
                        <h4 class="card-title">
                        <a href="#">Project One</a>
                        </h4>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet numquam aspernatur eum quasi sapiente nesciunt? Voluptatibus sit, repellat sequi itaque deserunt, dolores in, nesciunt, illum tempora ex quae? Nihil, dolorem!</p>
                    </div>
                    </div>
                </div>
                <div class="col-lg-4 col-sm-6 portfolio-item">
                    <div class="card h-100">
                    <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
                    <div class="card-body">
                        <h4 class="card-title">
                        <a href="#">Project Two</a>
                        </h4>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam viverra euismod odio, gravida pellentesque urna varius vitae.</p>
                    </div>
                    </div>
                </div>
                <div class="col-lg-4 col-sm-6 portfolio-item">
                    <div class="card h-100">
                    <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
                    <div class="card-body">
                        <h4 class="card-title">
                        <a href="#">Project Three</a>
                        </h4>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quos quisquam, error quod sed cumque, odio distinctio velit nostrum temporibus necessitatibus et facere atque iure perspiciatis mollitia recusandae vero vel quam!</p>
                    </div>
                    </div>
                </div>
                <div class="col-lg-4 col-sm-6 portfolio-item">
                    <div class="card h-100">
                    <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
                    <div class="card-body">
                        <h4 class="card-title">
                        <a href="#">Project Four</a>
                        </h4>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam viverra euismod odio, gravida pellentesque urna varius vitae.</p>
                    </div>
                    </div>
                </div>
                <div class="col-lg-4 col-sm-6 portfolio-item">
                    <div class="card h-100">
                    <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
                    <div class="card-body">
                        <h4 class="card-title">
                        <a href="#">Project Five</a>
                        </h4>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam viverra euismod odio, gravida pellentesque urna varius vitae.</p>
                    </div>
                    </div>
                </div>
                <div class="col-lg-4 col-sm-6 portfolio-item">
                    <div class="card h-100">
                    <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
                    <div class="card-body">
                        <h4 class="card-title">
                        <a href="#">Project Six</a>
                        </h4>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Itaque earum nostrum suscipit ducimus nihil provident, perferendis rem illo, voluptate atque, sit eius in voluptates, nemo repellat fugiat excepturi! Nemo, esse.</p>
                    </div>
                    </div>
                </div>
                </div>
                <div class="row">
                <div class="col-lg-6">
                    <h2>Modern Business Features</h2>
                    <p>The Modern Business template by Start Bootstrap includes:</p>
                    <ul>
                    <li>
                        <strong>Bootstrap v4</strong>
                    </li>
                    <li>jQuery</li>
                    <li>Font Awesome</li>
                    <li>Working contact form with validation</li>
                    <li>Unstyled page elements for easy customization</li>
                    </ul>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis, omnis doloremque non cum id reprehenderit, quisquam totam aspernatur tempora minima unde aliquid ea culpa sunt. Reiciendis quia dolorum ducimus unde.</p>
                </div>
                <div class="col-lg-6">
                    <img class="img-fluid rounded" src="http://placehold.it/700x450" alt="">
                </div>
                </div>
                <hr>
                <div class="row mb-4">
                <div class="col-md-8">
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias, expedita, saepe, vero rerum deleniti beatae veniam harum neque nemo praesentium cum alias asperiores commodi.</p>
                </div>
                <div class="col-md-4">
                    <a class="btn btn-lg btn-secondary btn-block" href="#">Call to Action</a>
                </div>
            </div>
        </div>-->
    
</template>


 <script>

  export default {
    

  }
  </script>
  
 
 
  <!--<div class="col-md-3 mb-md-0 mb-3">
                    <h5 class="text-uppercase">Links</h5>
                    <ul class="list-unstyled">
                    <li>
                    <a href="#!">Link 3</a>
                    </li>
                    </ul>
                    </div>-->



<style lang="scss" scoped>

                 #home, #prod, #Annonces{
  text-decoration: none!important;
  color: #FFF;
  margin: 0px 30px 0 30px;
  position: relative;
  top: 7.5px;
  &:hover{
    color:chartreuse;
  }
}

.navbar-nav{
  border: 1px solid #FFF;
  position: relative;
  margin-top: 10px;
  bottom: 15px;
  @media screen and (min-width: 300px) and (max-width: 840px){
    border: none;
     margin-top: 0px;
     bottom: 0px;
  }
}


#signin, #signup{
  text-decoration: none!important;
  color:#000;
}
  
#title{
  font-size: 2.5em;
}

.nav-link{
  margin-top: 0px;
  
}
 #accueil{
   //margin-left: 580px; 
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

#signin, #signup{
  
  &:hover{
    display: block;
    background-color: #35796a;
    color: #FFF;
  }
}

#navbarDropdown{
  font-size: .96em;
  position: relative;
  right: 7px;
  &:hover{
    color:chartreuse;
  }
  @media screen and (min-width: 300px) and (max-width: 500px){
    right: 0px;
    left: 30px;
  }
}

.dropdown-menu{
  text-align: center;
}

#navbarSupportedContent{
  position: relative;
  left: 15%;
  top: 10px;
}

</style>

   
