<template>

    <header>
        <div class="container">
            <a href="#"><img src="../assets/img/dc-logo.png" alt=""></a>

            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">CHARACTERS</a></li>
            </ul>
        </div>
    </header>
    
</template>

<script>
export default {
    
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