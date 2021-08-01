<template>
  <section>
    <h1>Nasza oferta</h1>
    <ul>
      <li>
        <app-bold-text text="Analiza ekspercka" font-size="20px" />
        najważniejszych ekranów i procesów
      </li>
      <li>
        <app-bold-text text="Opracowanie raportu" font-size="20px" />
        w formacie PDF
      </li>
      <li>
        <app-bold-text text="Lista błędów" font-size="20px" />
        jakie napotykają użytkownicy
      </li>
      <li>
        <app-bold-text text="Wykaz rekomendacji zmian" font-size="20px" /> i
        kieruneku rozwoju
      </li>
      <li>
        <app-bold-text text="Opis dobrych praktyk" font-size="20px" />
        zwiększających satysfakcję użytkownika
      </li>
      <li>
        <app-bold-text
          text="Analiza na podstawie danych Google Analytics"
          font-size="20px"
        />
      </li>
      <li>
        <app-bold-text
          text="Analiza wersji desktop i mobile"
          font-size="20px"
        />
      </li>
      <li>
        <app-bold-text
          text="Usprawnienia w formie makiet i drobnych projektów"
          font-size="20px"
        />
      </li>
    </ul>
    <div>
      <span class="gray"><app-bold-text text="już od" /></span>
      <app-bold-text text="80 zł / godz." font-size="36px" />
      <app-bold-text text="+ VAT" font-size="36px" />
      <span>
        <app-bold-text text="Indywidualna" font-size="20px" /> wycena dla
        Twojego e-biznesu
      </span>
      <app-button text="Wybierz" />
    </div>
  </section>
</template>

<script>
import AppButton from '../AppButton'
export default {
  name: 'Offer',
  components: {
    AppButton,
  },
}
</script>

<style scoped lang="scss">
li {
  font-size: 20px;
}
.gray {
  color: #242439;
  opacity: 0.4;
}
span {
  font-size: 20px;
}
</style>
