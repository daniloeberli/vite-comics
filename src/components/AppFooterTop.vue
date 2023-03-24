<script>
export default {
    data() {
        return {
            NavList: [
                {
                    tag: "DIGITAL COMICS",
                    link: "#",
                    img: "src/assets/buy-comics-digital-comics.png"
                },
                {
                    tag: "DC MERCHANDISE",
                    link: "#",
                    img: "src/assets/buy-comics-merchandise.png"
                },
                {
                    tag: "SUBSCRIPTION",
                    link: "#",
                    img: "src/assets/buy-comics-subscriptions.png"
                },
                {
                    tag: "COMIC SHOP LOCATOR",
                    link: "#",
                    img: "src/assets/buy-comics-shop-locator.png"
                },
                {
                    tag: "DC POWER VISA",
                    link: "#",
                    img: "src/assets/buy-dc-power-visa.svg"
                },
            ]
        }
    }
}
</script>

<template>
    <section>
        <div class="container-footer-top">
            <ul>
                <li v-for="item in NavList">
                    <a href="item.link">
                        <div class="img">
                            <img :src="item.img" alt="">
                        </div>
                        <div>
                            {{ item.tag }}
                        </div>
                    </a>
                </li>
            </ul>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    background-color: #0282f9;

    .container-footer-top {
        margin: 0 auto;
        width: 80%;
        padding: 50px 30px;
        height: 160px;
        display: flex;

        ul {
            list-style: none;
            display: flex;
            align-items: center;

            li{
                width: calc(100% / 5);
                padding: 40px 20px;

                a{
                    display: flex;
                    align-items: center;
                    text-decoration: none;
                    color: white;
                    font-size: 13px;

                    .img{
                    width: 50px;
                    margin-right: 20px;
                    img {
                        width: 100%;
                      
                    }
                }
                }
            }
        }

    
    }

}

</style>