<template>

    <header>
        <div class="container">
            <a href="#"><img src="../assets/img/dc-logo.png" alt=""></a>

            <ul>
                <li v-for="(link, index) in links" :key="index">
                    <a href="#">{{link.linkName}}</a>
                </li>
            </ul>
        </div>
    </header>
    
</template>

<script>
export default {
    name: 'myHeader',

    data(){
        return{
            links: [
                {
                    linkName: 'CHARACTERS'
                },
                {
                    linkName: 'COMICS'
                },
                {
                    linkName: 'MOVIES'
                },
                {
                    linkName: 'TV'
                },
                {
                    linkName: 'GAMES'
                },
                {
                    linkName: 'COLLECTIBLES'
                },
                {
                    linkName: 'VIDEOS'
                },
                {
                    linkName: 'FANS'
                },
                {
                    linkName: 'NEWS'
                },
                {
                    linkName: 'SHOP'
                }
            ]
        }
    }
}
</script>

<style scoped lang="scss">
    @import "../assets/style/colors.scss";
    header{
       
        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        ul{
            display: flex;
            list-style: none;
            align-items: center;
            height: 130px;
            

            li{
                line-height: 100%;
                height: 130px;
                display: flex;
                align-items: center;
                
                
                
                a{
                text-decoration: none;
                padding: 20px;
                color: $textBlack;
                line-height: 100%;
                height: 130px;
                display: flex;
                align-items: center;

                &:hover{
                    border-bottom: solid $myblue 5px;
                    color: $myblue;
                }
                }
            }
            
            
        }
    }
</style>