<script>

import ComicList from './ComicList.vue';

export default {
    components: {
        ComicList
    }
}
</script>

<template>
    <main>
        <h3>CURRENT SERIES</h3>

        <ComicList></ComicList>
        <div class="load">
            <a href="">LOAD MORE</a>
        </div>
    </main>
</template>

<style lang="scss" scoped>
main {
    background-color: #1c1c1c;
    padding-top: 60px;
    position: relative;

    .load {
        display: flex;
        justify-content: center;
        padding: 20px 0;

        a {
            text-decoration: none;
            color: white;
            padding: 10px 60px;
            background-color: #0282f9;
        }
    }

    h3 {
        color: white;
        position: absolute;
        top: -25px;
        left: 150px;
        padding: 15px 25px;
        background-color: #0282f9;
    }
}

div {
    margin: 0 auto;
    width: 80%;

}
</style>