<template>
    <div class="footer">
        <footer class="page-footer font-small pt-4 bg-saleemary">
            <div class="container-fluid text-center text-md-left">
                <div class="row">
                    <hr class="clearfix w-100 d-md-none pb-3">
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
    height: 60px;
}

a{
    position: relative;
    top: 1px;
    color: #FFF;
    &:hover{
        color: red;
    }
}

.footer-copyright{
    position: relative;
    bottom: 20px;
}

</style>