<template>
    <section class="nav-main">
        <div class="container">
            <ul class="main-list">
                <li class="list-item">
                    <img src="/img/buy-comics-digital-comics.png" width="50px" alt="">
                    <span> digital comics</span>                   
                </li>
                <li class="list-item">
                    <img src="/img/buy-comics-merchandise.png" width="50px" alt="">
                    <span> dc merchandise</span>                   
                </li>
                <li class="list-item">
                    <img src="/img/buy-comics-subscriptions.png" width="50px" alt="">
                    <span>subscription</span>                    
                </li>
                <li class="list-item">
                    <img src="/img/buy-comics-shop-locator.png" width="30px" alt="">
                    <span>comic shop locator</span>                    
                </li>
                <li class="list-item">
                    
                    <span>dc power visa</span>                    
                </li>
            </ul>
        </div>
    </section>
</template>
  
<script>
export default {

}
</script>
  
<style lang="scss" scoped>
.nav-main {
    background-color: rgb(2, 130, 249);

}

.main-list{
    display: flex;
    justify-content: space-around;
    text-transform: uppercase;
    padding: 50px 0;

    .list-item{
        display: flex;
        color: white;
        align-items: center;
        gap: 10px;
    }
}


</style>