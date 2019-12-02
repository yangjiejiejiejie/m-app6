<template>
    <div class="da">
         <div class="shang">
             我是Home
         </div>
         <div class="zhong">
             中部
         </div>
         <div class="xia">
             下部
         </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang='scss' scoped>
.da{
    width:100%;
    height:100%;
    display:flex;
    flex-direction:column;
}
.shang{
    width:100%;
    height:50px;
    background:blue;
}
.zhong{
    flex:1;
}
.xia{
    width:100%;
    height:50px;
    background:blue;
}
</style>
