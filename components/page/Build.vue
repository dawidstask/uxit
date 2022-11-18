<template>
  <div class="wrapper">
    <div class="left">
      <div class="wrapper__left">
        <div class="wrapper__left--top">
          <img class="logo" :src="require('@/static/build_logo.svg')" alt="logo">
          <span class="first">We Are Busy Working On Something Awesome</span>
          <span class="second">Strona w budowie</span>
          <button @click="onButtonClick()">Instagram</button>
        </div>
        <div class="footer">
          <img :src="require('~/static/build_footer.svg')" alt="footer">
        </div>
      </div>
    </div>
    <div class="right">
      <span>
        We handcraft unique design & digital experience to surprise the universe
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: "Build",
  methods: {
    onButtonClick() {
      window.open('https://www.instagram.com/lets_uxit/');
    }
  }
}
</script>

<style lang="scss" scoped>
.wrapper {
  display: flex;
  flex-direction: column;

  @media screen and (min-width: 700px) {
    flex-direction: row;
  }
}
.left {
  background: #E5E5E5;
  width: 100%;

  @media screen and (min-width: 700px) {
    width: 50%;
  }

  display: flex;
  .wrapper__left {
    display: flex;
    flex-direction: column;
    padding: 30px;
    justify-content: space-between;
    width: 100%;

    @media screen and (min-width: 700px) {
      padding: 64px;
    }

    &--top {
      display: flex;
      flex-direction: column;
    }
  }
  .logo {
    width: 101px;
    height: 66px;
    margin-bottom: 54px;
  }
  .first {
    font-weight: 500;
    font-size: 14px;
    line-height: 17px;
    color: #242439;
    margin-bottom: 24px;
  }
  .second {
    font-weight: 900;
    font-size: 40px;
    line-height: 49px;
    margin-bottom: 116px;
  }
  button {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 11px 63px;
    gap: 10px;
    width: 223px;
    height: 44px;
    background: #92C8BE;
    border-radius: 4px;
    flex: none;
    order: 0;
    flex-grow: 0;
    border: none;
    font-size: 18px;
    font-weight: 500;
    line-height: 22px;
    letter-spacing: 0em;
    text-align: left;
    cursor: pointer;
    align-self: center;

    @media screen and (min-width: 500px) {
      align-self: unset;
    }
  }
  .footer {
    display: none;

    @media screen and (min-width: 700px) {
      display: flex;
      width: 159px;
      height: 69px;
      align-self: center;
    }
  }
}
.right {
  background: linear-gradient(180deg, #E5D2CB 81.99%, #D7C6BB 100%);
  width: 100%;

  @media screen and (min-width: 700px) {
    width: 50%;
  }

  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  span {
    color: #242439;
    font-weight: 700;
    font-size: 32px;
    line-height: 49px;
    padding: 30px;

    @media screen and (min-width: 700px) {
      padding: 100px;
    }
  }
}
</style>
