<template>
  <section>
    <h1>Potrzebujesz zespołu do implementacji?</h1>
    <p><app-bold-text text="Polecimy firmy" /> z którymi współpracujemy!</p>
    <app-button text="Napisz do nas" />
  </section>
</template>

<script>
import AppButton from '../AppButton'
export default {
  name: 'NeedATeam',
  components: {
    AppButton,
  },
}
</script>

<style scoped lang="scss">
p {
  font-size: 24px;
}
</style>
