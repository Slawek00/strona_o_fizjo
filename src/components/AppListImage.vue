<template>
<div id="list-image">
  <div class="box-ad-L"></div>
  <div id="main-list">
  <h3>Wykaz zdjęć użytych na stronie:</h3>

  <ul>
    <li>3377382.jpg autorstwa strony Freepik,</li>
    <li>15880.jpg autorstwa macrovector na Freepik</li>
    <li>front-view-of-woman-having-neck-pain.jpg autrostwa strony Freepik</li>
    <li>woman-getting-massage-from-physiotherapist-with-ball-on-neck.jpg autorstwa strony Freepik</li>
    <li>hospital-room-interior.jpg autorstwa wirestock na Freepik</li>
  </ul>
  </div>
  <div class="box-ad-L"></div>
</div>
</template>

<script>
export default {
  name: "AppListImage"
}
</script>

<style scoped>
@font-face {
  font-family: "PermanentMarker";
  src: local("PermanentMarker"),
  url(../fonts/PermanentMarker-Regular.ttf) format("truetype");
}

#list-image{
  display: flex;
  flex-wrap: wrap;
}

.box-ad-L{
  width: 15%;
}

#main-list{
  width: 70%;
}

#main-list h3{
  text-align: center;
  font-family: Akaya;
}
</style>