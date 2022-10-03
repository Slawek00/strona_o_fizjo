<template>
<div id="about-vue" class="d-flex justify-content-center">
  <div id="container-aboutV" data-aos="zoom-in-down">
    <div class="d-flex justify-content-center ">

      <table>
        <tr>
          <td rowspan="2"><img src="../assets/vuejs-logo-17D586B587-seeklogo.com.png" alt="Obraz"></td>
          <td>

            <h2>O Vue</h2>
            <article>
              Vue jest fraemworkiem bazującym na języku JavaScript. Służy on do budowy
              reaktywnych aplikacji webowych.
            </article>

          </td>
        </tr>
        <tr>
          <td>
            <div class="d-flex justify-content-center">

              <a href="https://vuejs.org/guide/introduction.html#what-is-vue">
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
  name: "AppAboutVue"
}
</script>

<style scoped>

@font-face {
  font-family: "PermanentMarker";
  src: local("PermanentMarker"),
  url(../fonts/PermanentMarker-Regular.ttf) format("truetype");
}

#container-aboutV{
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