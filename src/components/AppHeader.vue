<script>
   export default{

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

header{
    background-color: pink;
}

div{
    padding: 20px 0;
    margin: 0 auto;
    width: 80%;
    display: flex;
    justify-content: space-between;
    ul{
        display: flex;
        align-items: center;
        list-style: none;
        li{
            a{
                display: inline-block;
                padding: 0 15px;
                text-decoration: none;
            }
        }
    }
}    

</style>