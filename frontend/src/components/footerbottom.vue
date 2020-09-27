<template>
    <div class="footer">
        <footer class="page-footer font-small pt-4 bg-saleemary">
            <div class="container-fluid text-center text-md-left">
                <div class="row">
                    <hr class="clearfix w-100 d-md-none pb-3">
                    <!--<div class="col-md-3 mb-md-0 mb-3">
                    <h5 class="text-uppercase">Links</h5>
                    <ul class="list-unstyled">
                    <li>
                    <a href="#!">Link 3</a>
                    </li>
                    </ul>
                    </div>-->
                </div>
                <div class="footer-copyright text-center py-3">© 2020 Copyright:
                    <a href="http://www.salimweb.fr/">Trocomania</a>
                </div>
            </div>
        </footer>
    </div> 
</template>

<script>
export default {
  name: 'footerbottom'
  
}
</script>

<style lang="scss" scoped>

.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    color: #FFF;
}

a{
    color: #FFF;
    &:hover{
        color: red;
    }
}



</style>