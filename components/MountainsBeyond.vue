<template>
  <div class="mountins-beyond__main-title">
    <div class="hiking-guide__wrapper">
      <div class="hiking-guide__text-after-line">
        <div class="hiking-guide__line"></div>
        <p class="paragraf-with-text">A Hiking guide</p>
      </div>
    </div>
    <div class="be-prepared__main">
      <div class="be-prepared__wrapper">
        <div class="be-prepared__text">
          Be prepared for the Mountains and beyond!
        </div>
      </div>
    </div>
    <div class="scroll-down__main">
      <div class="scroll-down__text">
        <p>scroll down</p>
      </div>
      <div class="scroll-down__symbol">&#8595;</div>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style lang="scss">
.mountins-beyond {
  &__main-title {
  }
}
.hiking-guide {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  &__wrapper {
    display: inline-block;
  }

  &__line {
    position: relative;
    top: 1px;
    display: inline-block;
    width: 72px;
    height: 2px;
    background-color: #fbd784;
    vertical-align: super;
  }

  &__text-after-line {
    .paragraf-with-text {
      display: inline-block;
      color: #fbd784;
      font-weight: 800;
      font-size: 18px;
      line-height: 22px;
      letter-spacing: 6px;
      text-transform: uppercase;
      margin-bottom: 32px;
    }
    // font-family: Gilroy;
  }
}
.be-prepared {
  &__main {
  }

  &__wrapper {
  }

  &__text {
    font-weight: 600;
    font-size: 88px;
    line-height: 100px;
    text-transform: capitalize;
    color: #fff;
  }
}
.scroll-down {
  &__main {
  }

  &__text {
  }

  &__symbol {
  }
}
</style>
