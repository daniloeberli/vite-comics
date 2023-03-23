<script>
    export default{

    }
</script>

<template>
    <footer>
        <div class="container-footer-top">
           <div class="footer-top-element">
                <img src="../assets/buy-comics-digital-comics.png" alt="digital comics">
                <h3>digital comics</h3>
           </div>
           <div class="footer-top-element">
                <img src="../assets/buy-comics-merchandise.png" alt="merch">
                <h3>merch</h3>
           </div>
           <div class="footer-top-element">
                <img src="../assets/buy-comics-subscriptions.png" alt="subs">
                <h3>Sub</h3>
           </div>
           <div class="footer-top-element">
                <img src="../assets/buy-comics-shop-locator.png" alt="location">
                <h3>comic shop location</h3>
           </div>
           <div class="footer-top-element">
                <img src="../assets/buy-dc-power-visa.svg" alt="visa">
                <h3>visa</h3>
           </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>

footer{
    background-color: #0282f9;
    .container-footer-top{
        margin: 0 auto;
        width: 80%;
        padding: 50px 30px;
        height: 160px;
        display: flex;
        div{
            align-items: center;
            margin: 0 auto;
            display: flex;
        }

        img{
            width: 50px;
        }

        h3{
            padding: 0 10px;
            color: white;
        }
    }
    
}

</style>