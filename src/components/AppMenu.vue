<template>

    <nav class = "navbar navbar-expand-lg navbar-light bg-success bg-gradient sticky-top">
      <div class="container-fluid">
        <h2 href="#" class = "navbar-brand text-white">Fizjoterapia</h2>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarContent">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarContent">
          <ul class="navbar-nav ms-auto head" >
            <li class="nav-item"><a class="nav-link" href="#">Czym jest fizjoterapia?</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Kariera zawodowa</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Najpopularniejsze metody leczenia</a></li>
            <li class="nav-item"><a class="nav-link" href="#">O stronie</a></li>
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

.container-fluid{
  font-family: PermanentMarker;
  font-size: 20px;
}


.container-fluid a:hover{
  color: whitesmoke;
}

</style>