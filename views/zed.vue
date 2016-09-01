<template>
    <div>
        <div>this is template body</div>
    </div>
</template>
<style lang="less">
    @color:#ccc;
    body{
        background-color: @color;
    }
</style>
<script>
    export default{
        data(){
            return{
                msg:'hello vue'
            }
        }
    }
</script>
