<script>
    export default{

    }
</script>

<template>
    <section>
        <div class="bottom-container">
            <div class="sign-btn">
                <h3>Sign up now</h3>
            </div>
            <div class="follow">
                <h3>follow us</h3>
                <img src="../assets/footer-facebook.png" alt="">
                <img src="../assets/footer-twitter.png" alt="">
                <img src="../assets/footer-youtube.png" alt="">
                <img src="../assets/footer-pinterest.png" alt="">
                <img src="../assets/footer-periscope.png" alt="">
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>

section{
    height: 110px;
    background-color: #303030;
    .bottom-container{
        width: 80%;
        height: 100%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .sign-btn{

            border: 2px solid #0282f9;

            h3{
                padding: 10px;
                color: white;
            }
        }
        .follow{
            display: flex;
            align-items: center;

            h3{
                padding-right: 10px;
                color: #0282f9;
                
            }

            img{
                padding: 0 10px;
            }
        }
    }
}

</style>