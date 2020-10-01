<template>
    <div class="connexion">
        <form class="form-signin">
            <h1>Connexion</h1>
            <label for="inputEmail" class="sr-only">e-mail</label>
            <input type="email" id="inputEmail" class="form-control" placeholder="email" required autofocus>
            <label for="inputpseudo" class="sr-only">pseudo</label>
            <input type="text" id="inputpseudo" class="form-control" placeholder="Pseudo" required autofocus>
            <label for="inputPassword" class="sr-only">Mot de passe</label>
            <input type="password" id="inputPassword" class="form-control" placeholder="mot de passe" required>
            <div class="checkbox mb-3">
              <label><input id="check" type="checkbox" value="remember-me">Rester connecté</label>
            </div>
            <button class="btn btn-lg btn-saleemary btn-block" type="submit">Connexion</button>
        </form>
    </div>
</template>


<script>

export default {
    name: 'connexions'
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
  margin-right: 5px;
} 

.checkbox{
  position: relative;
  bottom: 30px;
}

.btn{
  margin-top: 40px;
  margin-bottom: 200px;
}

</style>
