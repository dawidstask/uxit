<template>
  <div class="top">
    <Header />
    <section>
      <p class="title">Audyt UX</p>
      <h1>Popraw doświadczenie użytkownika swojej strony lub aplikacji</h1>
      <p class="description">
        Zdobądź <app-bold-text text="listę błędów" /> i rekomendację
        <app-bold-text text="zmian" />
      </p>
      <app-button text="Sprawdź ofertę" />
    </section>
  </div>
</template>

<script>
import AppBoldText from '../AppBoldText'
import AppButton from '../AppButton'
import Header from './Header'
export default {
  name: 'Top',
  components: {
    Header,
    AppBoldText,
    AppButton,
  },
}
</script>

<style scoped lang="scss">
.top {
  background: linear-gradient(180deg, #e5d2cb 64.58%, #d7c6bb 100%);
}
.title {
  font-size: 24px;
}
.description {
  font-size: 24px;
}
section {
  padding-bottom: 80px;
}
</style>
