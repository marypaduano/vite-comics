<template>
    <header>
        <div class="container">          
            <img src="/img/dc-logo.png" width="85px" alt="">
            <nav class="main-menu">
                <ul>
                    <li class="menu-item">characters</li>
                    <li class="menu-item active">comics</li>
                    <li class="menu-item">movies</li>
                    <li class="menu-item">tv</li>
                    <li class="menu-item">games</li>
                    <li class="menu-item">collectibles</li>
                    <li class="menu-item">videos</li>
                    <li class="menu-item">fans</li>
                    <li class="menu-item">news</li>
                    <li class="menu-item">shop</li>
                </ul>
            </nav>
        </div>
    </header>
</template>
  
<script>
export default {

}
</script>
  
<style lang="scss" scoped>
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

ul {
    display: flex;
    .menu-item {
        padding: 0 15px;
        font-size: 12px;
        text-transform: uppercase;
        font-weight: 900;

        &.active,
        &:hover {
            color: rgb(2, 130, 249);
        }
    }

}
</style>