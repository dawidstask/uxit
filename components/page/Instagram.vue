<template>
  <section>
    <p>
      Obserwuj nas na
      <app-bold-text text="instagramie" font-size="20px" /> gdzie
      <app-bold-text text="pomagamy w ulepszaniu" font-size="20px" />
      doświadczeń użytkownika
    </p>
    <app-button text="Zobacz profil" />
  </section>
</template>

<script>
import AppButton from '../AppButton'
export default {
  name: 'Instagram',
  components: {
    AppButton,
  },
}
</script>

<style scoped lang="scss">
p {
  font-size: 20px;
}
</style>
