<template>
  <div class="docker">
    <span class="docker__item docker__item--active">
      <div class="iconfont">&#xe607;</div>
      <div class="docker__title">首页</div>
    </span>
    <span class="docker__item">
      <div class="iconfont">&#xe63b;</div>
      <div class="docker__title">购物车</div>
    </span>
    <span class="docker__item">
      <div class="iconfont">&#xe6e4;</div>
      <div class="docker__title">订单</div>
    </span>
    <span class="docker__item">
      <div class="iconfont">&#xe600;</div>
      <div class="docker__title">我的</div>
    </span>
  </div>
</template>

<style lang="scss">
.docker {
  position: absolute;
  display: flex;
  padding: 0  .18rem;
  box-sizing: border-box;
  //background-color: antiquewhite;
  left: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 0.45rem;
  border-top: 1px solid gray;
  &__item {
    flex: 1;
    text-align: center;
    .iconfont {
      margin: .07rem 0 .02rem 0;
      font-size: .2rem;
    }
    &--active {
      color: deepskyblue;
    }
  }
  &__title {
    font-size: .2rem;
    //color: #42b983;
    transform: scale(0.5 , .5);
    transform-origin: center top;
  }
}
</style>
