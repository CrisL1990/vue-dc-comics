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

    .container{
        display: flex;
        justify-content: center;
    }
    button{
        padding: 10px 50px;
        background-color: rgb(3, 130, 349);
        border: none;
        color: white;
        font-weight: bold;
        margin-bottom: 30px;
    }
</style>