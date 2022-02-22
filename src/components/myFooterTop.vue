<template>

    <footer>
        <div class="container">

            <section id="footer-top">

                <div v-for="(item, index) in items" :key="index" class="box">
                    <a href="#"><img :src="item.logo" alt="#"></a>
                    <span>{{item.text}}</span>
                </div>

                <!--
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
                    <a href="#"><img id="visa" src="../assets/img/buy-dc-power-visa.svg" alt="DC logo footer"></a>
                    <span>DC POWER VISA</span>
                </div>
                -->
            </section>
        </div>
    </footer>
    
</template>

<script>
export default {
    name: 'myFooterTop',

    data(){
        return{

            items:[

                {
                    logo:require("../assets/img/buy-comics-digital-comics.png"),
                    text:"DIGITAL COMICS"
                },
                {
                    logo:require("../assets/img/buy-comics-merchandise.png"),
                    text:"DC MERCHANDISE"
                },
                {
                    logo:require("../assets/img/buy-comics-subscriptions.png"),
                    text:"SUBSCROPTION"
                },
                {
                    logo:require("../assets/img/buy-comics-shop-locator.png"),
                    text:"COMIC SHOP LOCATOR"
                },
                {
                    logo:require("../assets/img/buy-dc-power-visa.svg"),
                    text:"DC POWER VISA"
                }
            ]
        }
    }
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
                        #visa{
                            width: 75px;
                            margin-right: 20px;
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