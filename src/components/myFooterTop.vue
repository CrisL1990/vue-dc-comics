<template>

    <footer>
        <div class="container">

            <section id="footer-top">

                <myFooterCard 
                v-for="(item, index) in items" 
                :logo="item.logo" :text="item.text" 
                :key="index">
                </myFooterCard>

                <!--
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

import myFooterCard from './partials/myFooterCard.vue'
export default {
    name: 'myFooterTop',
    components:{
        myFooterCard
    },

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
            }
        }
    }

</style>