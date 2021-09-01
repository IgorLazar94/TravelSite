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
        <img src="../static/jpeg/firstsection.jpg" ; alt="Travel man" />
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.first-section {
  &__wrapper {
    background-color: #0c1e27;
  }

  &__main-flex {
    position: relative;
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    max-height: 720px;
    @media (max-width: 1140 + "px") {
      max-height: 509px;
    }
  }

  &__content {
    position: relative;
    margin: 141px 0 0 150px;
    max-width: 632px;
    padding: 5px;
    @media (max-width: 1140 + "px") {
      margin: 50px 0 0 25px;
    }
    @media (max-width: 750 + "px") {
      margin: 10px 0 0 5px;
    }
    @media (max-width: 680 + "px") {
      margin: 50px 0 0 25px;
    }
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
    @media (max-width: 1140 + "px") {
      font-size: 120px;
      top: -120px;
      left: -5px;
    }
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
    @media (max-width: 750 + "px") {
      font-size: 14px;
      margin-bottom: 10px;
    }
  }

  &__title {
    font-weight: 600;
    font-size: 64px;
    line-height: 77px;
    color: white;
    margin-bottom: 27px;
    @media (max-width: 990 + "px") {
      font-size: 40px;
      margin-bottom: 5px;
      line-height: 40px;
    }
  }

  &__text {
    font-weight: bold;
    font-size: 18px;
    line-height: 32px;
    color: #fff;
    margin-bottom: 27px;
    @media (max-width: 990 + "px") {
      font-size: 16px;
    }
    @media (max-width: 325 + "px") {
      margin-bottom: 5px;
      font-size: 14px;
    }
  }
  &__link {
    font-size: 18px;
    line-height: 22px;
    a {
      position: relative;
      color: #fbd784;
      text-decoration: none;
      &::after {
        margin-left: 16px;
        vertical-align: middle;
        content: url("../static/icons/arrow-right.svg");
        width: 10px;
        height: 10px;
      }
    }
  }
  &__image {
    img {
      @media (max-width: 1140 + "px") {
        max-width: 400px;
      }
      @media (max-width: 680+ "px") {
        display: none;
      }
    }
  }
}
</style>
