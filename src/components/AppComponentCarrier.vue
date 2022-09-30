<template>
  <div class="d-flex justify-content-center">
    <div id="container">
      <div class="d-flex justify-content-center ">

        <table>
          <tr>
            <td rowspan="2"><img src="../photo/3377382.jpg"></td>
            <td>

              <h2>Kariera zawodowa</h2>
              <article>
                Swoją karierę zawodową rozpoczynasz od nauki. Zaczynasz ją na kierunku fizjoterapii w dowolnym uniwersytecie
                medycznym.
                Po ukończeniu studiów musisz według polskiego prawa
                pracować 6 lat w innym gabinecie fizjoterapii, jeżeli masz tylko licencjat, a dwa jeżeli magisterkę.
              </article>

            </td>
          </tr>
         <tr>
           <td>
             <div class="d-flex justify-content-center">

                 <a href="https://abk.umed.pl/baza-wiedzy-2/polecane-artykuly/perspektywy-zawodowe-po-fizjoterapii/">
                 <button type="button" class="btn btn-primary">Czytaj więcej</button></a>

             </div>
           </td>
          </tr>
        </table>

      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "AppComponentKarier"
}

</script>

<style scoped>

@font-face {
  font-family: "PermanentMarker";
  src: local("PermanentMarker"),
  url(../fonts/PermanentMarker-Regular.ttf) format("truetype");
}

#container{
  margin-top: 100px;
  margin-bottom: 100px;
  height: 500px;
  width: 800px;
  background-color: deepskyblue;
}

td{
  margin: 0;
  padding-top: 50px;
}

td h2{
  font-family: PermanentMarker;
}

td:first-child{
  padding-right: 25px;
  padding-left: 25px;
}

table tr:first-child img{
  height: 400px;
  width: 380px;
}

</style>