<template>

  
    <div class="thumb">
        <div class="img-cont">
            <img :src="thumb" alt="#">
        </div>
        <span>{{series}}</span>
    </div>

  
</template>

<script>
export default {
   name: "myThumbnail",
   props: {
        thumb: String, 
        series: String
    }

}
</script>

<style scoped lang="scss">
    @import "../../assets/style/colors.scss";

    .thumb{
        display: flex;
        flex-direction: column;
        position: relative;
        height: 300px;
        width: calc(100% / 6);
            

        .img-cont{
            position: absolute;
            top: 0;
            left: 0;
            height: 200px;
            overflow: hidden;
        }

        span{
            color: $textWhite;
            position: absolute;
            top: 220px;
            display: inline-block;
            max-width: 90%;
        }
    }
</style>