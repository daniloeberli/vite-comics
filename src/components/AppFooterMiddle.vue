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
                        <h2>DC comics</h2>
                        <ul>
                            <li v-for="item in DcComicsList">
                                <a :href="item.link">{{ item.tag }}</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h2>shop</h2>
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
    background-image: url(../assets/footer-bg.jpg);

    .footer-middle-container {
        width: 80%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;

        .middle-left {
            display: flex;
        }
    }

    h2 {
        color: white;
    }

    ul {
        list-style: none;

        a {
            color: #3a6586;
            text-decoration: none;
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