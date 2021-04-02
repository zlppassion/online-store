<template>
    <div id="warp-box">
        <!--这里是全局视图层-->
        <router-view :key="$route.fullPath"></router-view>
    </div>
</template>
<style>

</style>
<script>
export default {
   // 监听,当路由发生变化的时候执行
// watch:{
//   $route(to,from){
//     console.log('zheli:', to.path);
//     window.reload;
//   }
// },
    
}
</script>