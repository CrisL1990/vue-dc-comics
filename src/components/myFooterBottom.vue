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
    
}
</script>

<style lang="scss" scoped>

    .footer-bottom{
        height: 150px;
        background-color: rgb(48, 48, 48);

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
                border: solid rgb(3, 130, 249) 3px;
                color: white;
            }

            .right-box{
                justify-content: end;

                #follow{
                    padding: 0 10px;
                    color: rgb(3, 130, 249);
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