<script setup>

</script>

<template>
  <div class="box">
    <a class="download" href="https://jsdelivr.007666.xyz/gh/ChenDoXiu/MoeKey@main/docs/MoeKey.exe" download="MoeKey.exe" >下载</a>
  </div>
</template>

<style scoped>
.box{
  height: 100vh;
  width: 100vw;
  min-width: 800px; /* 你想要的最小宽度 */
  background-image: url("https://jsdelivr.007666.xyz/gh/ChenDoXiu/MoeKey@main/docs/banner.png");
  background-repeat: no-repeat;
  background-size: cover; /* 或者 contain */
}
.download{
  position: absolute;
  bottom: 158px;
  left: 410px;
  transform: translateX(-50%);
  padding: 10px 20px;
  border-radius: 5px;
  background-color: #fff;
  color: #000;
  text-decoration: none;
  font-size: 18px;
  font-weight: bold;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}
</style>