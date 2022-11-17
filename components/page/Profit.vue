<template>
  <section>
    <h1>To zyskasz:</h1>
    <dl>
      <dt><app-tick /><span>Wykrycie problemów</span></dt>
      <dd>
        <app-bold-text text="Lista błędów" font-size="20px" />, które negatywnie
        wpływają na odbiór użytkowników Twojej strony bądź aplikacji
      </dd>
      <dt><app-tick /><span>Rekomendacja zmian</span></dt>
      <dd>
        Informacje na temat tego jak
        <app-bold-text text="niewielkim nakładem prac" font-size="20px" />
        poprawić błędy i optymalizować produkt
      </dd>
      <dt><app-tick /><span>Poprawa satysfakcji</span></dt>
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
import AppTick from '../AppTick'
export default {
  name: 'Profit',
  components: {
    AppBoldText,
    AppTick,
  },
}
</script>

<style scoped lang="scss">
section {
  box-shadow: 1px 0 34px 0 #0000001a;
  border-radius: 20px;
}
dt {
  margin-bottom: 17px;
  span {
    font-size: 20px;
    font-family: 'Inter Bold', sans-serif;
    text-transform: uppercase;
    margin-left: 22px;
  }
}
dd {
  font-size: 20px;
  font-family: 'Inter Regular', sans-serif;
  margin-inline-start: 0;
  margin-bottom: 40px;
}
</style>
