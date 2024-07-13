<template>
  <div class='tabbar'>
    <ul>
        <li>
          <van-icon name="wap-home-o" />
          <span>首页</span>
        </li>
        <li>
          <van-icon name="wap-home-o" />
          <span>首页</span>
        </li>
        <li>
          <van-icon name="wap-home-o" />
          <span>首页</span>
        </li>
        <li>
          <van-icon name="wap-home-o" />
          <span>首页</span>
        </li>   
    </ul>
  </div>
</template>

<script>

</script>


<style scoped >
.tabbar{
  position:fixed;
  left:0;
  bottom:0;
  z-index:999;
  width:100%;
  height:75px;
  background-color: aliceblue;
}
.tabbar ul{
  display: flex;
}
.tabbar ul li{
	flex: 1;
  display: flex;
  flex-direction:column;
}
</style>
