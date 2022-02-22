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
    
    header{
       
        .container{
            padding: 15px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        ul{
            display: flex;
            list-style: none;
            align-items: center;
            height: 100%;
            

            li{
                line-height: 100%;
                
                a{
                text-decoration: none;
                padding: 20px;
                color: black;
                line-height: 100%;
                }
            }
            
            
        }
    }
</style>