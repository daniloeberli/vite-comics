<script>
export default {

}
</script>

<template>
    <footer>
        <div class="footer-middle-container">
            <div class="middle-left">
                <div>
                    <div>
                        <h2>DC comics</h2>
                        <ul>
                            <li><a href="#">Prova</a></li>
                            <li><a href="#">Prova</a></li>
                            <li><a href="#">Prova</a></li>
                            <li><a href="#">Prova</a></li>
                            <li><a href="#">Prova</a></li>
                            <li><a href="#">Prova</a></li>
                            <li><a href="#">Prova</a></li>
                        </ul>
                    </div>
                    <div>
                        <h2>shop</h2>
                        <ul>
                            <li><a href="#">Prova</a></li>
                            <li><a href="#">Prova</a></li>
                        </ul>
                    </div>
                </div>
                <div>
                    <h2>DC</h2>
                    <ul>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                    </ul>
                </div>
                <div>
                    <h2>SITES</h2>
                    <ul>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                        <li><a href="#">Prova</a></li>
                    </ul>
                </div>
            </div>
            <div>
                <h2>hey</h2>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer {
    height: 300px;
    background-image: url(../assets/footer-bg.jpg);

    .footer-middle-container {
        width: 80%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        .middle-left{
            display: flex;
        }
    }

    h2{
        color: white;
    }

    ul{
        list-style: none;

        a{
            color: #3a6586;
            text-decoration: none;
        }
    }
}
</style>