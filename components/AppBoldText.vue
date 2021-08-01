<template>
  <span :style="`font-size: ${fontSize}`">{{ text }}</span>
</template>

<script>
export default {
  name: 'AppBoldText',
  props: {
    text: {
      type: String,
      required: true,
    },
    fontSize: {
      type: String,
      default: '24px',
    },
  },
}
</script>

<style scoped>
span {
  font-family: 'Inter Bold', sans-serif;
}
</style>
