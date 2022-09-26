<template>
  <div>
    <nav class="navbar navbar-expand-lg" style="background-color: #66b2f1;">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Fizjoterapia</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#">Czym jest fizjoterapia?</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Historia</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Najpopularniejsze metody leczenia</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Znajdź swojego fizjoterapeutę!</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "AppMenu"
}
</script>

<style scoped>
@font-face {
  font-family: "PermanentMarker";
  src: local("PermanentMarker"),
  url(../fonts/PermanentMarker-Regular.ttf) format("truetype");
}

.navbar-brand{
  font-family: PermanentMarker;
}




</style>