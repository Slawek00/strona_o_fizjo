<template>
<div id="about-bootstrap" class="d-flex justify-content-center">
  <div id="container-aboutB">
  <div class="d-flex justify-content-center ">

    <table>
      <tr>
        <td rowspan="2"><img src="../assets/bootstrap-logo.png" alt="Obraz"></td>
        <td>

          <h2>O Bootstrap</h2>
          <article>
            W skrócie: są to gotowe elementy mające przyszpieszyć pracę nad stronami internetowymi.

          </article>

        </td>
      </tr>
      <tr>
        <td>
          <div class="d-flex justify-content-center">

            <a href="https://getbootstrap.com/docs/5.2/getting-started/introduction/">
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
  name: "AppAboutBootstrap"
}
</script>

<style scoped>

@font-face {
  font-family: "PermanentMarker";
  src: local("PermanentMarker"),
  url(../fonts/PermanentMarker-Regular.ttf) format("truetype");
}

#container-aboutB{
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