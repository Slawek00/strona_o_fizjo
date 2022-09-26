<template>
  <div id="banner">
      <img src="../../public/logov2.png">
    <div>
      <span>Fizjoterpia</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppBanner"
}
</script>

<style scoped>
@font-face {
  font-family: "PermanentMarker";
  src: local("PermanentMarker"),
  url(../fonts/PermanentMarker-Regular.ttf) format("truetype");
}

#banner img{
  margin-top: 10px;
  height: 60px;
}

#banner span{
  font-family: PermanentMarker;
  font-size: 50px;
}

#banner{
  display: flex;
  justify-content: center;
}

</style>