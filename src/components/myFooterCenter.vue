<template>
    <section class="footer-center">
        <div class="container">

            <div class="left-box">
                <div class="links">
                    <div class="dc-comics">
                        <h1>DC COMICS</h1>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </div>
                    <div class="dc-comics">
                        <h1>SHOP</h1>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                    
                </div>
                
                <div class="links">
                    <h1>DC</h1>
                    <ul>
                        <li><a href="#">Terms of use</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div class="links">
                    <h1>SITES</h1>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>

            <div class="right-box">
                <div id="img-container">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
                
            </div>

        </div>
    </section>

</template>

<script>
export default {
    name: 'myFooterCenter',

    data(){
        return{
            
           
        }
    }
}
</script>

<style scoped lang="scss">

    .footer-center{
        background-image: url('../assets/img/footer-bg.jpg');
        height: 450px;
     
        &::after{
            display: table;
            content: "";
            clear: both;
        }

        .container{
        
            height: 100%;
        }

        .left-box, .right-box{
            width: 50%;
            float: left;
            height: 100%;
            display: flex;
            position: relative;
            
        }

        .left-box{
            padding-top: 20px;
            
            .links{
                width: calc(80% / 3);

                h1{
                    color: white;
                    padding: 20px 0;
                }

                li{
                    margin: 10px 0;
                }

                a{
                    text-decoration: none;
                    font-size: 15px;
                    color: gray;
                    
                }
            } 
        }

        .right-box{
            
            position: relative;

            #img-container{
                position: absolute;
                
                top: 0;
                bottom: 0;
                left: 0;
                right: 0;
                max-height: 100%;
                text-align: center;
                overflow: hidden;
                
                img{
                    vertical-align: middle;
                    position: absolute;
                    height: 150%;
                    top: 50%;
                    left: 50%;
                    transform: translate(-50%, -50%);
                }
            }
        }
    }

</style>