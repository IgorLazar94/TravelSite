<template>
  <div class="mountins-beyond__main-title">
    <div class="hiking-guide__wrapper">
      <div class="hiking-guide__line">
        <hr class="hr-line" />
      </div>
      <div class="hiking-guide__text-after-line">
        <p>A Hiking guide</p>
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
  &__wrapper {
  }

  &__line {
    .hr-line {
      display: inline;
      color: #fbd784;
      width: 72px;
      height: 2px;
      size: 2px;
      transform: rotate(90deg);
    }
  }

  &__text-after-line {
    // font-family: Gilroy;
    display: inline;
    color: #fbd784;
    font-weight: 800;
    font-size: 18px;
    line-height: 22px;
    letter-spacing: 6px;
    text-transform: uppercase;
    margin-bottom: 32px;
  }
}
.be-prepared {
  &__main {
    background-color: darkgrey;
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
