<template>
  <div class="wrapper">
<!--    <div class="left">-->
<!--      <div class="wrapper__left">-->
<!--        <img class="logo" :src="require('~/static/build_logo.svg')" alt="logo">-->
<!--        <span class="first">We Are Busy Working On Something Awesome</span>-->
<!--        <span class="second">Strona w budowie</span>-->
<!--        <button>Instagram</button>-->
<!--        <div class="footer">-->
<!--          <img :src="require('~/static/build_footer.svg')" alt="footer">-->
<!--        </div>-->
<!--      </div>-->
<!--    </div>-->
    <div class="right">
      <span>
        We handcraft unique design & digital experience to surprise the universe
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: "Build"
}
</script>

<style lang="scss" scoped>
.wrapper {
  display: flex;
}
.left {
  background: #E5E5E5;
  //width: 50%;
  height: 100vh;
  .wrapper__left {
    display: flex;
    flex-direction: column;
    padding: 64px;
  }
  .logo {
    width: 101px;
    height: 66px;
  }
  .first {
    font-weight: 500;
    font-size: 14px;
    line-height: 17px;
    color: #242439;
  }
  .second {
    font-weight: 900;
    font-size: 40px;
    line-height: 49px;
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
  }
  .footer {
    width: 159px;
    height: 69px;
    align-self: center;
  }
}
.right {
  background: linear-gradient(180deg, #E5D2CB 81.99%, #D7C6BB 100%);
  //width: 50%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  span {
    color: #242439;
    font-weight: 700;
    font-size: 32px;
    line-height: 49px;
    padding: 100px;
  }
}
</style>
