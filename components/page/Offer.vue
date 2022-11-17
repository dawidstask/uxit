<template>
  <section>
    <h1>Nasza oferta</h1>
    <ul>
      <li>
        <span>
          <app-bold-text text="Analiza ekspercka" font-size="20px" />
          najważniejszych ekranów i procesów
        </span>
        <app-tick-round />
      </li>
      <hr>
      <li>
        <span>
          <app-bold-text text="Opracowanie raportu" font-size="20px" />
          w formacie PDF
        </span>
        <app-tick-round />
      </li>
      <hr>
      <li>
        <span>
          <app-bold-text text="Lista błędów" font-size="20px" />
          jakie napotykają użytkownicy
        </span>
        <app-tick-round />
      </li>
      <hr>
      <li>
        <span>
          <app-bold-text text="Wykaz rekomendacji zmian" font-size="20px" /> i
          kieruneku rozwoju
        </span>
        <app-tick-round />
      </li>
      <hr>
      <li>
        <span>
          <app-bold-text text="Opis dobrych praktyk" font-size="20px" />
          zwiększających satysfakcję użytkownika
        </span>
        <app-tick-round />
      </li>
      <hr>
      <li>
        <span>
          <app-bold-text
            text="Analiza na podstawie danych Google Analytics"
            font-size="20px"
          />
        </span>
        <app-tick-round />
      </li>
      <hr>
      <li>
        <span>
          <app-bold-text
            text="Analiza wersji desktop i mobile"
            font-size="20px"
          />
        </span>
        <app-tick-round />
      </li>
      <hr>
      <li>
        <span>
          <app-bold-text
            text="Usprawnienia w formie makiet i drobnych projektów"
            font-size="20px"
          />
        </span>
        <app-tick-round />
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
import AppTickRound from '~/components/AppTickRound';
export default {
  name: 'Offer',
  components: {
    AppButton,
    AppTickRound,
  },
}
</script>

<style scoped lang="scss">
span {
  width: 70%;
}
ul {
  padding-left: 0;
}
li {
  display: flex;
  justify-content: space-between;
  font-size: 20px;
}
hr {
  border-top: 1px solid #E5E5E5;
  margin: 30px 0;
}
.gray {
  color: #242439;
  opacity: 0.4;
}
span {
  font-size: 20px;
}
</style>
