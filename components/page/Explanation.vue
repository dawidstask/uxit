<template>
  <section>
    <h1><span>Co to jest</span> <span>audyt UX?</span></h1>
    <p class="first">
      <app-bold-text text="Analiza ekspercka" font-size="20px" /> doświadczonego
      Specjalisty UX: aktywnego zawodowo projektanta i badacza
    </p>
    <p>
      Metodyka wykorzystywana w audycie opiera się na
      <app-bold-text
        text="analizie heurystycznej, wędrówce poznawczej"
        font-size="20px"
      />
      oraz <app-bold-text text="liście kontrolnej" font-size="20px" />
      sporządzonej przez naszych specjalistów
    </p>
    <p>
      Analizujemy zarówno
      <app-bold-text text="wersję desktopową jak i mobile" font-size="20px" />
    </p>
  </section>
</template>

<script>
export default {
  name: 'Explanation',
}
</script>

<style scoped lang="scss">
h1 {
  display: flex;
  flex-direction: column;
  span {
    font-family: 'Inter Bold', sans-serif;
    font-size: 40px;
  }
}
p {
  margin-top: 36px;
  margin-left: 40px;
  margin-right: 10px;
  font-size: 20px;
  &.first {
    margin-top: 56px;
  }
}
</style>
