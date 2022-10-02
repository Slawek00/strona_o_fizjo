<template>
  <div id="about-page">
    <div class="box-ad"></div>
    <div id="main-content">
    <h3>O stronie</h3>
    <article>

      Strona została utworzona tylko do portfolio.
      <i><b>Zawiera małą wartość merytoryczną jeżeli chodzi o tematy związane z fizjoterapią!
      Ze względu na to, że strona została utworzona w celu nauki programowania i obsługi freamworków Vue oraz Bootstrap.
      Autor strony nie zagłębiał się mocno w temat.</b></i>
      Jeżeli interesujesz się fizjoterapią zachęcam Ciebie do poczytania ustaw o zawodzie fizjoterapeuty oraz
      poszukania bardziej rzetelniejszych informacji.
      Większość tekstu została wygenerowana przez generator tekstu <a href="https://smodin.io/pl/pisarz">smodin</a>.
      Ikony Githuba oraz Linkedin pochodzą z strony <a href="https://fontawesome.com/icons">fontawesome</a>.
      Niestandardowe czcionki pochodzą z strony <a href="https://fonts.google.com/">google fonts</a>.
      Zdjęcia pochodzą ze <a href="https://pl.freepik.com/darmowe-zdjecie-wektory/fizjoterapia">stocku</a>. Ze względu na
      licencje podaję wykaz zdjęć użytych na stronie.
    </article>
    </div>
    <div class="box-ad"></div>
  </div>
</template>

<script>

export default {
  name: "AppAboutPage"
}

</script>

<style scoped>

@font-face {
  font-family: "Akaya";
  src: local("AkayaTelivigala"),
  url(../fonts/AkayaTelivigala-Regular.ttf) format("truetype");
}

#about-page{
  padding-bottom: 60px;
  display: flex;
  flex-wrap: wrap;
}

.box-ad{
  width: 15%;
}

#main-content{
  width: 70%;
}

h3{
  padding-top: 60px;
  text-align: center;
  font-family: Akaya;
}

</style>