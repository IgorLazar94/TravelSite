<!-- Please remove this file from your project -->
<template>
  <div class="header">
    <div class="header__wrapper">
      <div class="header__main">
        <div class="header__logo">MNTN</div>
        <div class="header__menu">
          <ul>
            <li>Equipment</li>
            <li>About us</li>
            <li>Blog</li>
          </ul>
        </div>
        <div class="header__account">Account</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.header {
  &__wrapper {
    background-color: indianred;
    color: white;
  }

  &__main {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  &__logo {
    font-family: Chronicle Display;
    font-size: 32px;
    line-height: 38px;
    letter-spacing: 0.01em;
  }

  &__menu {
    max-width: 280px;
    font-family: Gilroy;
    font-style: normal;
    font-weight: bold;
    font-size: 18px;
    line-height: 22px;

    ul {
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: row;
      justify-content: space-between;

      li {
        list-style: none;
        margin-right: 40px;
        white-space: nowrap;
      }
    }
  }

  &__account {
    &::before {
      content: url("~/static/icons/header-icon.svg");
      vertical-align: middle;
    }
  }
}
</style>
