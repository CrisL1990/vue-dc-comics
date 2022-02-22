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
            color: white;
            position: absolute;
            top: 220px;
        }
    }
</style>