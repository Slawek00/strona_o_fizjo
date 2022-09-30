<template>
  <footer>
    <div id="footer">
      <div class="d-flex justify-content-center">

          <a href="https://github.com/Slawek00/Slawek00"><img src="../assets/github.png" alt="Github"></a>
          <a href="https://www.linkedin.com/in/s%C5%82awomir-ja%C5%82ojda-224948243/"><img src="../assets/linkedin.png" alt="Linkedin"></a>

      </div>

      <h6>Stronę stworzył: Sławomir Jałojda</h6>

    </div>
  </footer>
</template>

<script>

export default {
  name: "AppFooter",
}

</script>

<style scoped>

@font-face {
  font-family: "Akaya";
  src: local("AkayaTelivigala"),
  url(../fonts/AkayaTelivigala-Regular.ttf) format("truetype");
}

#footer{
  --bs-bg-opacity: 1;
  background-color: rgba(var(--bs-success-rgb), var(--bs-bg-opacity)) !important;
  width: 100%;
}

#footer h6{
  font-family: Akaya;
  font-size: 20px;
  text-align: center;
}

#footer img{
  margin-top: 5px;
  height: 75px;
  width: 75px;
  padding: 10px;
}

#footer img:hover{
  background-color: darkseagreen;
  border-radius: 100px;
}

</style>