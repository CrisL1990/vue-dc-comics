<template>
    <div class="container">
        <button>LOAD MORE</button>
    </div>
</template>

<script>
    
    export default {
        name: 'myButton',
    }
</script>
    
<style scoped lang="scss">
    @import "../../assets/style/colors.scss";
    .container{
        display: flex;
        justify-content: center;
    }
    button{
        padding: 10px 50px;
        background-color: $myblue;
        border: none;
        color: $textWhite;
        font-weight: bold;
        margin-bottom: 30px;
    }
</style>