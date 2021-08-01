<template>
  <section>
    <h1>To zyskasz:</h1>
    <dl>
      <dt>Wykrycie problemów</dt>
      <dd>
        <app-bold-text text="Lista błędów" font-size="20px" />, które negatywnie
        wpływają na odbiór użytkowników Twojej strony bądź aplikacji
      </dd>
      <dt>Rekomendacja zmian</dt>
      <dd>
        Informacje na temat tego jak
        <app-bold-text text="niewielkim nakładem prac" font-size="20px" />
        poprawić błędy i optymalizować produkt
      </dd>
      <dt>Poprawa satysfakcji</dt>
      <dd>
        Po wdrożeniu zmian poprawisz doświdczenie użytkownika, zwiększysz
        <app-bold-text
          text="wzrost konwersji i zmniejszysz współczynnik odrzuceń"
          font-size="20px"
        />
      </dd>
    </dl>
  </section>
</template>

<script>
import AppBoldText from '../AppBoldText'
export default {
  name: 'Profit',
  components: {
    AppBoldText,
  },
}
</script>

<style scoped lang="scss">
section {
  box-shadow: 1px 0 34px 0 #0000001a;
  border-radius: 20px;
}
dt {
  font-size: 20px;
  font-family: 'Inter Bold', sans-serif;
  text-transform: uppercase;
}
dd {
  font-size: 20px;
  font-family: 'Inter Regular', sans-serif;
  margin-inline-start: 0;
}
</style>
