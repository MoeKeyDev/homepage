<script setup>

</script>

<template>
  <div style="display: flex">
    <div>
      <!--    底部背景1-->
      <div class="bottom_bg1">
        <div class="object1">
          <svg class="svg_animation_1" xmlns="http://www.w3.org/2000/svg" xml:space="preserve"
               style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:2;"
               viewBox="0 0 1000 1000" aria-hidden="true" data-v-2ad8b8d3=""><path d="M979.5-329c190.69 0 345.5 154.813 345.5 345.5S1170.19 362 979.5 362C788.813 362 542 165.187 542-25.5S788.813-329 979.5-329" style="fill:url(#a);" transform="translate(-433.5 483.5)"></path>
            <defs><linearGradient id="a" x1="0" x2="1" y1="0" y2="0" gradientTransform="matrix(783 0 0 691 542 16.5)" gradientUnits="userSpaceOnUse"><stop offset="0" style="stop-color:#2bb400;stop-opacity:1;"></stop><stop
                offset="1" style="stop-color:#71b400;stop-opacity:1;"></stop></linearGradient></defs></svg>
        </div>
        <div class="object2">
          <svg xmlns="http://www.w3.org/2000/svg" xml:space="preserve"
               style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:2;"
               viewBox="0 0 1000 1000" aria-hidden="true" data-v-2ad8b8d3=""><path d="M965.5-315c190.69 0 409.5 142.813 409.5 333.5S1170.19 362 979.5 362C788.813 362 634 207.187 634 16.5S774.813-315 965.5-315" style="fill:url(#a);" transform="translate(-504.5 476.5)"></path>
            <defs><linearGradient id="a" x1="0" x2="1" y1="0" y2="0" gradientTransform="matrix(741 0 0 677 634 23.5)" gradientUnits="userSpaceOnUse"><stop offset="0" style="stop-color:#71b400;stop-opacity:.5;"></stop><stop
                offset="1" style="stop-color:#25b400;stop-opacity:.5;"></stop></linearGradient></defs></svg>
        </div>
      </div>
      <!--    底部背景2-->
      <div class="bottom_bg2" >
        <img class="home-logo-img" src="https://jsdelivr.007666.xyz/gh/MoeKeyDev/MoeKey@main/assets/favicon.png">
        <h2 class="grid-svg1-h2">
          <div class="row" >MoeKey
            <br>Is a Misskey Client</div>
        </h2>
        <div class="grid-svg1-text" data-v-92a70bab="">
          Moekey is a client that uses the original Misskey design style and supports Misskey theme colours
        </div>
      </div>
      <div>
        <a class="button" style="color: white;background-color:  #00b428" href="https://github.com/MoeKeyDev/MoeKey/releases" target="_blank" rel="noopener noreferrer" >
          <span>Download</span>
        </a>
        <a class="button" style="color: #00b428;background-color: white;margin-left: 30px" href="https://github.com/MoeKeyDev/MoeKey" target="_blank" rel="noopener noreferrer" >
          <span>Github</span>
        </a>
      </div>
    </div>
<!--    展示图片-->
    <div class="show-img-box">
    </div>
  </div>
</template>

<style scoped>
.show-img-box{
  position: relative;
  width: 800px;
  height: 800px;
  left: 30px;
  top: 30px;
  background-color: red;
}
.button{
  position: relative;
  border-radius: 32px;
  display: inline-block;
  line-height: 36px;
  left: 42px;
  top: -17px;
  font-size: 18px;
  padding:8px 36px;
  height: 38px;
  z-index: 2;
  box-shadow: rgb(0 0 0 / 10%) 0px 0.15rem 0.45rem, rgb(0 0 0 / 10%) 0px 0.0625rem 0.15rem;
}
.bottom_bg1 {
  border-bottom-color: rgb(229, 231, 235);
  border-bottom-style: solid;
  border-bottom-width: 0px;
  border-image-outset: 0;
  border-image-repeat: stretch;
  border-image-slice: 100%;
  border-image-source: none;
  border-image-width: 1;
  border-left-color: rgb(229, 231, 235);
  border-left-style: solid;
  border-left-width: 0px;
  border-right-color: rgb(229, 231, 235);
  border-right-style: solid;
  border-right-width: 0px;
  border-top-color: rgb(229, 231, 235);
  border-top-style: solid;
  border-top-width: 0px;
  box-sizing: border-box;
  color: rgb(30, 41, 59);
  display: block;
  font-family: Nunito, "Noto Sans SC", ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-feature-settings: normal;
  font-variation-settings: normal;
  height: 100%;
  left: 0px;
  line-height: 24px;
  overflow-x: hidden;
  overflow-y: hidden;
  position: absolute;
  tab-size: 4;
  text-size-adjust: 100%;
  top: 0px;
  unicode-bidi: isolate;
  width: 100%;
  z-index: 0;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

.bottom_bg2{
  border: solid 0px rgb(229, 231, 235);
  border-image: none;
  box-sizing: border-box;
  color: rgb(30, 41, 59);
  display: block;
  font-family: Nunito, "Noto Sans SC", ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-feature-settings: normal;
  font-variation-settings: normal;
  height: 642.516px;
  line-height: 24px;
  margin: 0px 19px;
  padding: 32px;
  position: relative;
  tab-size: 4;
  text-size-adjust: 100%;
  unicode-bidi: isolate;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

.svg_animation_1 {
  animation: spin-2ad8b8d3 60s linear 0s infinite normal none running;
}

@keyframes spin-2ad8b8d3 {
  0% {
    transform: rotate(0)
  }

  to {
    transform: rotate(1turn)
  }
}

@media (min-width: 1024px) {
  .object1 {
    left: auto;
    opacity: 1;
    right: -300px;
    top: -400px;
    width: 1000px;
  }
}

.object1 {
  position: absolute;
}

.object2 {
  animation-name: parallax-2ad8b8d3;
  animation-timing-function: linear;
  border-bottom-color: rgb(229, 231, 235);
  border-bottom-style: solid;
  border-bottom-width: 0px;
  border-image-outset: 0;
  border-image-repeat: stretch;
  border-image-slice: 100%;
  border-image-source: none;
  border-image-width: 1;
  border-left-color: rgb(229, 231, 235);
  border-left-style: solid;
  border-left-width: 0px;
  border-right-color: rgb(229, 231, 235);
  border-right-style: solid;
  border-right-width: 0px;
  border-top-color: rgb(229, 231, 235);
  border-top-style: solid;
  border-top-width: 0px;
  box-sizing: border-box;
  color: rgb(30, 41, 59);
  display: block;
  font-family: Nunito, "Noto Sans SC", ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-feature-settings: normal;
  font-variation-settings: normal;
  height: 1000px;
  left: -250px;
  line-height: 24px;
  opacity: 0.5;
  pointer-events: none;
  position: absolute;
  tab-size: 4;
  text-size-adjust: 100%;
  top: 500px;
  unicode-bidi: isolate;
  user-select: none;
  width: 1000px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

.grid-svg1-h2{
  border-bottom-color: rgb(229, 231, 235);
  border-bottom-style: solid;
  border-bottom-width: 0px;
  border-image-outset: 0;
  border-image-repeat: stretch;
  border-image-slice: 100%;
  border-image-source: none;
  border-image-width: 1;
  border-left-color: rgb(229, 231, 235);
  border-left-style: solid;
  border-left-width: 0px;
  border-right-color: rgb(229, 231, 235);
  border-right-style: solid;
  border-right-width: 0px;
  border-top-color: rgb(229, 231, 235);
  border-top-style: solid;
  border-top-width: 0px;
  box-sizing: border-box;
  color: rgb(30, 41, 59);
  display: block;
  font-family: Capriola, "Noto Sans SC", ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-feature-settings: normal;
  font-size: 60px;
  font-variation-settings: normal;
  font-weight: 700;
  letter-spacing: 1.5px;
  line-height: 97.5px;
  margin-block-end: 0px;
  margin-block-start: 24px;
  margin-bottom: 0px;
  margin-inline-end: 0px;
  margin-inline-start: 0px;
  margin-left: 0px;
  margin-right: 0px;
  margin-top: 24px;
  tab-size: 4;
  text-align: start;
  text-size-adjust: 100%;
  unicode-bidi: isolate;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
.grid-svg1-text{
  border-bottom: solid 0px rgb(229, 231, 235);
  border-image: none;
  border-left: solid 0px rgb(229, 231, 235);
  border-right: solid 0px rgb(229, 231, 235);
  border-top: solid 0px rgb(229, 231, 235);
  box-sizing: border-box;
  color: rgb(30, 41, 59);
  display: block;
  font: 18px Nunito, "Noto Sans SC", ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-feature-settings: normal;
  font-variation-settings: normal;
  height: 28px;
  line-height: 28px;
  margin: 24px 0px 0px 0px;
  tab-size: 4;
  text-align: start;
  text-size-adjust: 100%;
  unicode-bidi: isolate;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

.home-logo-img{
  width: 230px;
  height: 230px;
  border-radius: 12px;
}
</style>