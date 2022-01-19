<template>
  <div id="app">
    <div class="p-0 m-0">
      <Page/>
    </div>
  </div>
</template>

<script>
import Page from "./components/Page.vue"
export default {
  name: 'App',
  components: {
    Page
  }
}
</script>

<style>
@font-face {
  font-family: Kohinoor_Bangla;
  src: url(./assets/font/Kohinoor_Bangla/KohinoorBangla-Regular.otf);
}

*{
  font-family: Kohinoor_Bangla;
}
.navBar{
  background-color: #343232;
}
.section{
  background-color: #F5FDFA;
}

.sideNav-userInfo {
  background-image: linear-gradient(to bottom right, #EA12B0, #FFB40B);
}
</style>
