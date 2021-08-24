<template>
  <div class="mountins-wrapper">
    <div class="mountins-beyond__header">
      <HeaderComponent> </HeaderComponent>
    </div>
    <div class="mountins-beyond__main-block">
      <div class="mountins-beyond__main-block-social"></div>
      <div class="mountins-beyond__main-title">
        <MountainsBeyond> </MountainsBeyond>
      </div>
      <div class="mountins-beyond__main-pagination"></div>
    </div>
    <div class="mountins-beyond__firs-section"></div>
    <div class="mountins-beyond__second-section"></div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped lang="scss">
body {
  margin: 0 auto;
}
.mountins-wrapper {
  margin: 0 auto;
  max-width: 1760px;
}
.mountins-beyond {
  &__header {
    margin: 64px 0px 198px 0px;
    border: 1px solid;
    height: 25px;
    max-width: 1760px;
  }

  &__main-block {
    border: 1px solid red;
    height: 310px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0px 0px 843px 0px;
  }

  &__main-block-social {
    border: 1px solid;
    width: 24px;
    height: 173px;
  }

  &__main-title {
    width: 950px;
    height: 310px;
    border: 1px solid green;
  }

  &__main-pagination {
    border: 1px solid;
    width: 77px;
    height: 240px;
  }

  .mountins-container {
    max-width: 1462px;
  }

  &__firs-section {
    margin: 0 auto;
    margin-bottom: 200px;
    width: 1462px;
    height: 720px;
    border: 1px solid red;
  }
  &__second-section {
    margin: 0 auto;
    margin-bottom: 200px;
    width: 1462px;
    height: 720px;
    border: 1px solid red;
  }
}
</style>
