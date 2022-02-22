<template>
    <div class="box">
        <a href="#"><img :id="(text == 'DC POWER VISA') ? 'visa' : '' " :src="logo" alt="#"></a>
        <span>{{text}}</span>
    </div>
  
</template>

<script>
export default {
    name: 'myFooterCard',
    props:{
        logo: String,
        text: String
    }
}
</script>

<style scoped lang="scss">
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

                #visa{
                width: 50%;
                height: 50%;
            }
            }
        }
        span{
            color: white;
        }
    }
</style>