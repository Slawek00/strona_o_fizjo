<template>
  <main role="main">
    <article>

      <h3>Czym jest fizjoterapia?</h3>
      <p>
        Fizjoterapia to dziedzina medycyny polegająca na leczeniu pacjenta pod kierunkiem fizjoterapeutów.
        Fizjoterapia odbywa się w szpitalach i ośrodkach rehabilitacyjnych i polega na stosowaniu środków fizycznych na organizm ludzki w celu poprawy zdrowia,
        ruchu i funkcji. Niektórzy pacjenci decydują się na fizjoterapię w domu podczas rekonwalescencji.
      </p>

      <h3>Jak wykonuje się fizjoterapie</h3>
      <p>
        Fizjoterapia jest wykorzystywana do pomocy ludziom w powrocie do zdrowia po urazach i chorobach poprzez manipulowanie uszkodzonymi lub chorymi obszarami ciała.
        Pacjenci otrzymują leczenie od fizjoterapeutów po specjalistycznym szkoleniu;
        Ci praktycy są certyfikowani poprzez rozszerzone kursy i nadzorowane doświadczenia kliniczne.
        Metoda leczenia może być stosowana u dorosłych i dzieci i koncentruje się na mięśniach, stawach, ścięgnach, nerwach, układzie limfatycznym, układzie krążenia, układzie oddechowym, układzie pokarmowym i stanie skóry.
        Zabiegi zazwyczaj wykonuje się w pozycji siedzącej, ze stopami płasko na podłodze; pozwala to na bardziej efektywną terapię.
      </p>

      <h3>Gdzie odybwa się fizjoterapia</h3>
      <p>
        Szpitale są głównym miejscem fizjoterapii, ponieważ jest dużo sprzętu i miejsca dla pacjentów.
        W placówkach tych znajdują się pokoje, w których pacjenci ze wszystkimi rodzajami schorzeń lub urazów mogą wyzdrowieć.
        Istnieją również pracownicy, którzy pomagają pacjentom w czasie ich powrotu do zdrowia.
        Fizjoterapia na ogół polega na serii ćwiczeń, które celują w określone części ciała przy użyciu różnych narzędzi,
        takich jak taśmy oporowe i temblaki.
        Sesje trwają zwykle od 45 minut do 1 godziny dziennie i można je wykonywać trzy razy dziennie.
      </p>

      <h3>Narzędzia do fizjoterapii</h3>
      <p>
        Fizjoterapeuci używają różnych narzędzi, takich jak temblaki,
        opaski oporowe i opaski elastyczne, aby rozciągać lub wzmacniać mięśnie, jednocześnie minimalizując ból.
        Używają również masaży, gorących okładów, stymulacji elektrycznej i strumieni wodnych, aby złagodzić ból i poprawić krążenie krwi w ciele.
        Praktycy zalecają również spożywanie pożywnego jedzenia, utrzymywanie odpowiedniego nawodnienia, zasypianie na czas i ograniczanie stresu w celu poprawy zdrowia pacjenta.
        Po leczeniu urazu lub choroby pacjenci mogą przechodzić regularne sesje fizjoterapii na zalecenie lekarza, aby zachować zdrowie.
      </p>

      <h3>Przyczyny zabiegów</h3>
      <p>
        Według National Center for Complementary and Integrative Health (NCCIH),
        około 100 milionów obywateli USA otrzymało fizjoterapię w pewnym momencie swojego życia.
        Większość ludzi otrzymuje fizjografię z powodu urazów lub chorób przewlekłych, takich jak ból pleców, zapalenie stawów, zespół cieśni nadgarstka, urazy rowerowe, problemy z kolanem, dystrofia mięśni, ból szyi i urazy barku.
        Oprócz leczenia dolegliwości fizycznych w placówkach opieki zdrowotnej, niektórzy ludzie decydują się na fizjoterapię po urazie lub chorobie, aby mogli szybciej się goić przy mniejszym bólu i zmęczeniu.
        Istnieją również kliniki, które specjalizują się w regeneracji po kontuzji sportowców, aby szybciej wrócić do formy.
      </p>
      <p>
        Fizjoterapia to skuteczna metoda leczenia, która pomaga wyzdrowieć po urazach i chorobach.
        Pacjenci otrzymują leczenie od fizjoterapeutów po specjalistycznym szkoleniu;
        Ci praktycy są certyfikowani poprzez rozszerzone kursy i nadzorowane doświadczenia kliniczne.
        Metodę leczenia można zastosować u dorosłych i dzieci z różnymi schorzeniami lub urazami w domu podczas rekonwalescencji.
      </p>

    </article>
    <AppComponentCarrier/>
    <AppMethods/>
    <AppAboutPage/>
  </main>
</template>



<script>
import AppComponentCarrier from "@/components/AppComponentCarrier.vue";
import AppMethods from "@/components/AppMethods.vue";
import AppAboutPage from "@/components/AppAboutPage.vue";

export default {
  name: "AppContent",
  components:{
    AppComponentCarrier,
    AppMethods,
    AppAboutPage
  }
}

</script>



<style scoped>

@font-face {
  font-family: "Akaya";
  src: local("AkayaTelivigala"),
  url(../fonts/AkayaTelivigala-Regular.ttf) format("truetype");
}

h3{
  font-family: Akaya;
}

</style>