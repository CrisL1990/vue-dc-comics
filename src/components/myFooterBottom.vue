<template>
    <section class="footer-bottom">

            <div class="container">
                <div class="left-box">
                    <button>SIGN-UP NOW!</button>
                </div>

                <div class="right-box">
                    <span id="follow">FOLLOW US</span>

                    <div class="icon-box">
                        <i class="fa-brands fa-facebook-f"></i>
                    </div>
                    <div class="icon-box">
                        <i class="fa-brands fa-twitter"></i>
                    </div>
                    <div class="icon-box">
                        <i class="fa-brands fa-youtube"></i>
                    </div>
                    <div class="icon-box">
                        <i class="fa-brands fa-pinterest-p"></i>
                    </div>
                    <div class="icon-box">
                        <i class="fa-solid fa-location-dot"></i>
                    </div>
                
                </div>
        </div>
        

    </section>
</template>

<script>
export default {
    name: 'mtFooterBottom'
}
</script>

<style lang="scss" scoped>
    @import "../assets/style/colors.scss";
    .footer-bottom{
        height: 150px;
        background-color: $bgGrayLighter;

        .container{

            height: 100%;

            &::after{
                display: table;
                content: "";
                clear: both;
            }

            .left-box, .right-box{
            height: 100%;
            width: 50%;
            float: left;
            display: flex;
            align-items: center;
            }

            button{
                padding: 15px;
                background-color: transparent;
                border: solid $myblue 3px;
                color: $textWhite;
            }

            .right-box{
                justify-content: end;

                #follow{
                    padding: 0 10px;
                    color: $myblue;
                    font-weight: 600;
                    font-size: 18px;
                }

                .icon-box{
                    width: 30px;
                    height: 30px;
                    border-radius: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    background-color: gray;
                    margin: 0 5px;
                }
               
            }
            
        }

        
    }
</style>