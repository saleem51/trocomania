<template>
    <div class="inscription">
        <form class="form-signin">
            <h1>Inscription</h1>
            <label for="inputEmail" class="sr-only">e-mail</label>
            <input type="email" id="inputEmail" class="form-control" placeholder="email" required autofocus>
            <label for="inputname" class="sr-only">Nom</label>
            <input type="text" id="inputname" class="form-control" placeholder="nom" required autofocus>
            <label for="inputfirstname" class="sr-only">prénom</label>
            <input type="text" id="inputfirstname" class="form-control" placeholder="Prénom" required autofocus>
            <label for="inputpseudo" class="sr-only">pseudo</label>
            <input type="text" id="inputpseudo" class="form-control" placeholder="Pseudo" required autofocus>
            <input type="firstname" id="inputEmail" class="form-control" placeholder="prénom" required autofocus>
            <label for="inputPassword" class="sr-only">Mot de passe</label>
            <input type="password" id="inputPassword" class="form-control" placeholder="mot de passe" required>
            <div class="checkbox mb-3">
              <label><input id="check" type="checkbox" value="remember-me"> Se souvenir de moi</label>
            </div>
            <button class="btn btn-lg btn-saleemary btn-block" type="submit">Valider</button>
        </form>
    </div>
</template>


<script>

export default {
    name: 'inscriptions'
}

</script>


<style lang="scss" scoped>


.form-signin {
  width: 100%;
  max-width: 330px;
  padding: 15px;
  margin: auto;
  position: relative;
  top: 50px;
}

h1{
position: relative;
bottom: 60px;
left: 30px;
}

.form-signin .checkbox {
  font-weight: 400;
}
.form-signin .form-control {
  position: relative;
  box-sizing: border-box;
  height: auto;
  padding: 10px;
  font-size: 16px;
}
.form-signin .form-control:focus {
  z-index: 2;
}
.form-signin input[type="email"], {
  margin-bottom: -1px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
  margin: 10px 0px 10px 0px;
}
.form-signin input[type="password"] {
  margin-bottom: 10px;
  border-top-left-radius: 0;
  border-top-right-radius: 0;
}

input {
     margin: 10px 0px 10px 0px;
     position: relative;
     bottom: 40px;
}

#check{
  bottom: 0px;
} 

.checkbox{
  position: relative;
  bottom: 35px;
}

.btn{
  position: relative;
  bottom: 53px;
  margin-bottom: 200px;
  height: 45px;
  left: 70px;
  width: 45%;

}

#inputPassword, #inputEmail, #inputname, #inputfirstname, #inputpseudo{
 height: 35px;
}

</style>
