<template>
    <section class="footer-center">
        <div class="container">

            <div class="left-box">
                <div class="links">
                    <div class="dc-comics">
                        <h1>DC COMICS</h1>
                        <ul>
                            <li><a href="#">Ciao</a></li>
                            <li><a href="#">Ciao</a></li>
                            <li><a href="#">Ciao</a></li>
                            <li><a href="#">Ciao</a></li>
                        </ul>
                    </div>
                    <div class="dc-comics">
                        <h1>SHOP</h1>
                        <ul>
                            <li><a href="#">Ciao</a></li>
                            <li><a href="#">Ciao</a></li>
                            <li><a href="#">Ciao</a></li>
                            <li><a href="#">Ciao</a></li>
                        </ul>
                    </div>
                    
                </div>
                
                <div class="links">
                    <h1>DC</h1>
                    <ul>
                        <li><a href="#">Ciao</a></li>
                        <li><a href="#">Ciao</a></li>
                        <li><a href="#">Ciao</a></li>
                        <li><a href="#">Ciao</a></li>
                        <li><a href="#">Ciao</a></li>
                    </ul>
                </div>
                <div class="links">
                    <h1>SITES</h1>
                    <ul>
                        <li><a href="#">Ciao</a></li>
                        <li><a href="#">Ciao</a></li>
                        <li><a href="#">Ciao</a></li>
                        <li><a href="#">Ciao</a></li>
                        <li><a href="#">Ciao</a></li>
                    </ul>
                </div>
            </div>

            <div class="right-box">
                <img src="../assets/img/dc-logo-bg.png" alt="DC logo footer big">
            </div>

        </div>
    </section>

</template>

<script>
export default {
    
}
</script>

<style scoped lang="scss">

    .footer-center{
        background-image: url('../assets/img/footer-bg.jpg');
        
        &::after{
            display: table;
            content: "";
            clear: both;
        }

        .left-box, .right-box{
            width: 50%;
            float: left;
            display: flex;
        }

        .left-box{
            height: 100%;
            padding-top: 20px;

            .links{
                width: calc(80% / 3);

                h1{
                    color: white;
                    padding: 20px 0;
                }

                a{
                    text-decoration: navajowhite;
                    font-size: 18px;
                    color: gray;
                }
            }
        }

        .right-box{
            justify-content: center;
          
        }
    }

</style>