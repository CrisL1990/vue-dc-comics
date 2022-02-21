<template>
    <main>
        <div class="container">
            <h2>Content goes here</h2>
        </div>
    </main>
</template>

<script>
export default {
    name: 'myMain'
}
</script>

<style scoped lang="scss">
    main{
        min-height: 100px;
        background-color: black;
        display: flex;

        .container{
            
            align-items: center;
            height: 100%;

            h2{
                color: white;

            }
        }
    }
</style>