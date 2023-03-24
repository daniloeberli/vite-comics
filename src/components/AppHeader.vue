<script>
export default {
    
    data() {
        return {
            list: [
                {
                    tag: "CHARACTERS",
                    link: "#"
                },
                {
                    tag: "COMICS",
                    link: "#"
                },
                {
                    tag: "MOVIES",
                    link: "#"
                },
                {
                    tag: "TV",
                    link: "#"
                },
                {
                    tag: "GAMES",
                    link: "#"
                },
                {
                    tag: "COLLECTIBLES",
                    link: "#"
                },
                {
                    tag: "VIDEOS",
                    link: "#"
                },
                {
                    tag: "FANS",
                    link: "#"
                },
                {
                    tag: "NEWS",
                    link: "#"
                },
                {
                    tag: "SHOP",
                    link: "#"
                }
            ]
        }
    }

}
</script>

<template>
    <section>
        <div>
            <img src="../assets/dc-logo.png" alt="logo dc">
            <ul>
                <li v-for="item of list">
                    <a href="item.link">{{ item.tag }}</a>
                </li>
            </ul>
        </div>
    </section>
</template>

<style lang="scss" scoped>
div {
    margin: 0 auto;
    width: 80%;
    display: flex;
    justify-content: space-between;

    img {
        padding: 20px 0;
    }

    ul {
        display: flex;
        align-items: center;
        list-style: none;

        li {
            height: 100%;
            display: flex;
            align-items: center;

            &:hover {
                border-bottom: 5px solid #0282f9;
                a{
                    color: #0282f9;
                }
            }

            a {
                display: inline-block;
                padding: 0 15px;
                text-decoration: none;
                color: #464646;

                
            }
        }
    }
}
</style>