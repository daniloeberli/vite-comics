<script>
export default {
    data() {
        return {
            DcComicsList: [
                {
                    tag: "Characters",
                    link: "#"
                },
                {
                    tag: "Comics",
                    link: "#"
                },
                {
                    tag: "Movies",
                    link: "#"
                },
                {
                    tag: "TV",
                    link: "#"
                },
                {
                    tag: "Games",
                    link: "#"
                },
                {
                    tag: "Videos",
                    link: "#"
                },
                {
                    tag: "News",
                    link: "#"
                }
            ],
            ShopList: [
                {
                    tag: "Shop DC",
                    link: "#"
                },
                {
                    tag: "Shop DC collectibles",
                    link: "#"
                }
            ],
            DcList: [
                {
                    tag: "Terms Of Use",
                    link: "#"
                },
                {
                    tag: "Privacy policy (New)",
                    link: "#"
                },
                {
                    tag: "Ad choises",
                    link: "#"
                },
                {
                    tag: "Advertising",
                    link: "#"
                },
                {
                    tag: "Jobs",
                    link: "#"
                },
                {
                    tag: "Subscriptions",
                    link: "#"
                },
                {
                    tag: "Talent Workshops",
                    link: "#"
                },
                {
                    tag: "CPSC Certificates",
                    link: "#"
                },
                {
                    tag: "Ratings",
                    link: "#"
                },
                {
                    tag: "Shop Help",
                    link: "#"
                },
                {
                    tag: "Contact Us",
                    link: "#"
                },
            ],
            SitesList: [
                {
                    tag: "DC",
                    link: "#"
                },
                {
                    tag: "MAD Magazine",
                    link: "#"
                },
                {
                    tag: "DC Kids",
                    link: "#"
                },
                {
                    tag: "DC Universe",
                    link: "#"
                },
                {
                    tag: "DC Power Visa",
                    link: "#"
                }
            ]
        }
    }
}
</script>

<template>
    <section>
        <div class="footer-middle-container">
            <div class="middle-left">
                <div>
                    <div class="comic-list">
                        <h2>DC COMICS</h2>
                        <ul>
                            <li v-for="item in DcComicsList">
                                <a :href="item.link">{{ item.tag }}</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h2>SHOP</h2>
                        <ul>
                            <li v-for="item in ShopList">
                                <a :href="item.link">{{ item.tag }}</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="dc-list">
                    <h2>DC</h2>
                    <ul v-for="item in DcList">
                        <li>
                            <a :href="item.link">{{ item.tag }}</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <h2>SITES</h2>
                    <ul>
                        <li v-for="item in SitesList">
                            <a :href="item.link">{{ item.tag }}</a>
                        </li>
                    </ul>
                </div>
            </div>
            <div>

            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    height: 300px;
    background: url(../assets/dc-logo-bg.png) center right 15% no-repeat , url(../assets/footer-bg.jpg) left top no-repeat ;
    background-size: auto, cover; 
    .footer-middle-container {
        width: 80%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;

        .middle-left {
            display: flex;
            padding-top: 30px;
        }
    }

    h2 {
        color: white;
        padding-bottom: 10px;
        font-size: 16px;
    }

    ul {
        list-style: none;

        a {
            color: lighten(#698888,10%);
            text-decoration: none;
            font-size: 12px;
        }
    }

    .comic-list {
        padding-bottom: 20px;
    }

    .dc-list {
        padding: 0 40px;
    }
}
</style>

background-image: url(logo), url(bg);
    background-position: % %,  % %;
    background-size: %, %;
    height: ?;
    background-repeat: no-repeat;