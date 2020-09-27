<template>
  <div class="footer">
    <nav id="nav" class="navbar navbar-expand-lg navbar-dark bg-saleemary">
      <!--<img id="img" src="../assets/header2.png">-->
      <p class="copy">© Copyright Trocomania 2020</p>
    </nav>
  </div> 
</template>

<script>
export default {
  name: 'footerbottom'
  
}
</script>

<style lang="scss" scoped>

#nav{
    display: flex;
     justify-content: center;
}

.navbar{
    position: fixed;
    bottom: 0;
    width: 100%;
    height: 50px;
}

.copy{
    color: #FFF;
    position: relative;
}

#link{
    text-decoration: none;    
    color: #FFF;
    &:hover{
        color: yellow;
    }
}

</style>