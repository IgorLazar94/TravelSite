<template>
  <div class="first-section__wrapper">
    <div class="first-section__main-flex">
      <div class="first-section__content">
        <div class="first-section__number-absolute">01</div>
        <div class="first-section__before-name"></div>
        <div class="first-section__name">get started</div>
        <div class="first-section__title">What level of hiker are you?</div>
        <div class="first-section__text">
          Determining what level of hiker you are can be an important tool when
          planning future hikes. This hiking level guide will help you plan
          hikes according to different hike ratings set by various websites like
          All Trails and Modern Hiker. What type of hiker are you – novice,
          moderate, advanced moderate, expert, or expert backpacker?
        </div>
        <div class="first-section__link"><a href="#">read more</a></div>
      </div>
      <div class="first-section__image">
        <img src=url(./static/jpeg/firstsection.jpg); alt="Travel man">
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.first-section {
  &__wrapper {
    background-color: rgb(114, 105, 105);
  }

  &__main-flex {
    position: relative;
    display: flex;
    justify-content: space-between;
  }

  &__content {
    position: relative;
  }

  &__number-absolute {
    position: absolute;
    font-weight: bold;
    font-size: 240px;
    line-height: 240px;
    opacity: 0.1;
    color: #fff;
    top: -100px;
    left: -120px;
  }

  &__before-name {
    position: relative;
    top: 1px;
    display: inline-block;
    width: 72px;
    height: 2px;
    background-color: #fbd784;
    vertical-align: super;
  }

  &__name {
    display: inline-block;
    font-weight: 800;
    font-size: 18px;
    line-height: 22px;
    letter-spacing: 6px;
    text-transform: uppercase;
    color: #fbd784;
    margin-bottom: 27px;
  }

  &__title {
    font-weight: 600;
    font-size: 64px;
    line-height: 77px;
    color: white;
    margin-bottom: 27px;
  }

  &__text {
    font-weight: bold;
    font-size: 18px;
    line-height: 32px;
    color: #fff;
    margin-bottom: 27px;
  }
  //  -------------------------------------------отобразить svg после ссылки --------------------------------------------
  &__link {
    font-size: 18px;
    line-height: 22px;
    a {
      color: #fbd784;
      text-decoration: none;
      &::after {
        content: "";
        background-image: url(static/icons/arrow-right.svg);
      }
    }
  }
  //  -------------------------------------------отобразить картинку --------------------------------------------
  &__image {
    // background-image: url("static/jpeg/FirstSection.jpg");
    // background-repeat: no-repeat;
    // position: absolute;
    // display: block;
  }
}
</style>
