<template>
  <span>
    <a href="">{{ text }}</a>
  </span>
</template>

<script>
export default {
  name: 'AppButton',
  props: {
    text: {
      type: String,
      required: true,
    },
  },
}
</script>

<style scoped lang="scss">
span {
  width: 224px;
  height: 44px;
  background-color: #92c8be;
  border-radius: 4px;
  display: flex;

  a {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-decoration: none;
    font-size: 18px;
  }
}
</style>
