<template>
    <nav class = "navbar navbar-expand-lg navbar-light bg-success bg-gradient sticky-top">
      <div class="container-fluid">
        <a href="#" class = "navbar-brand text-white">Fizjoterapia</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarContent">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarContent">
          <ul class="navbar-nav ms-auto head" >
            <li class="nav-item"><a class="nav-link" href="#">Czym jest fizjoterapia?</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Historia</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Najpopularniejsze metody leczenia</a></li>
            <li class="nav-item"><a class="nav-link" href="#">O autorze</a></li>
          </ul>
        </div>
      </div>
    </nav>
</template>

<script>

export default {
  name: "AppMenu",
}
</script>

<style scoped>
@font-face {
  font-family: "PermanentMarker";
  src: local("PermanentMarker"),
  url(../fonts/PermanentMarker-Regular.ttf) format("truetype");
}

.container-fluid a{
  font-family: PermanentMarker;
  font-size: 20px;
}

.container-fluid a:hover{
  color: whitesmoke;
}


</style>