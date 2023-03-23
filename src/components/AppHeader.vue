<script>
export default {

}
</script>

<template>
    <header>
        <div>
            <img src="../assets/dc-logo.png" alt="logo dc">
            <ul>
                <li><a href="#">a</a></li>
                <li><a href="#">a</a></li>
                <li><a href="#">a</a></li>
                <li><a href="#">a</a></li>
                <li><a href="#">a</a></li>
                <li><a href="#">a</a></li>
                <li><a href="#">a</a></li>
                <li><a href="#">a</a></li>
                <li><a href="#">a</a></li>
                <li><a href="#">a</a></li>
            </ul>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header {
    
}

div {
    margin: 0 auto;
    width: 80%;
    display: flex;
    justify-content: space-between;

    img{
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
            &:hover{
                    border-bottom: 5px solid #0282f9;
                }

            a {
                display: inline-block;
                padding: 0 15px;
                text-decoration: none;
                color: #464646;
                &:hover{
                    color: #0282f9;
                }
            }
        }
    }
}
</style>