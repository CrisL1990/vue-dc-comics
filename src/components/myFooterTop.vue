<template>

    <footer>
        <div class="container">

            <section id="footer-top">

                <div class="box">
                    <a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt="DC logo footer"></a>
                    <span>DIGITAL COMICS</span>
                </div>
                <div class="box">
                    <a href="#"><img src="../assets/img/buy-comics-merchandise.png" alt="DC logo footer"></a>
                    <span>DC MERCHANDISE</span>
                </div>
                <div class="box">
                    <a href="#"><img src="../assets/img/buy-comics-subscriptions.png" alt="DC logo footer"></a>
                    <span>SUBSCROPTION</span>
                </div>
                <div class="box">
                    <a href="#"><img src="../assets/img/buy-comics-shop-locator.png" alt="DC logo footer"></a>
                    <span>COMIC SHOP LOCATOR</span>
                </div>
                <div class="box">
                    <a href="#"><img class="visa" src="../assets/img/buy-dc-power-visa.svg" alt="DC logo footer"></a>
                    <span>DC POWER VISA</span>
                </div>
                
            </section>
        </div>
    </footer>
    
</template>

<script>
export default {
    
}
</script>

<style scoped lang="scss">

    footer{
        display: flex;
        min-height: 100px;
        background-color: rgb(3, 130, 249);

        .container{

            #footer-top{
                display: flex;

                .box{
                    height: 150px;
                    width: calc(100% / 5);
                    display: flex;
                    justify-content: center;
                    align-items: center;

                    a{
                        text-align: center;
                        .visa{
                            width: 30%;
                        }
                        img{
                            width: 50%;
                            height: 50%;
                        }
                    }
                    span{
                        color: white;
                    }
                }
            }
        }
    }

</style>