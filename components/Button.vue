<!-- Please remove this file from your project -->
<template>
  <div class="button-main">
    <div class="button-wrapper">
      <div class="button-wrapper__text">
        <button class="text-button item-button">Click me!</button>
        <button class="text-button item-button">Click me!</button>
      </div>
    </div>
  </div>
</template>

<style lang='scss'>
.button-main {
}
.button-wrapper {
  &__text {
    margin: 0 auto;
    width: 410px;
    border-bottom: 1px solid grey;
  }
}
.text-button {
  background: none;
  border: none;
  //   border-radius: 10px;
  width: 200px;
  height: 50px;
  margin-bottom: -1px;
  &:focus {
    border-bottom: 2px solid greenyellow;
  }
  //   border-bottom: 2px solid grey;
}
</style>

