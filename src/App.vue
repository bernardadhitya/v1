<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
@font-face {
  font-family: "Bold";
  src: url(./assets/fonts/Galano-Grotesque-Bold.otf);
}
@font-face {
  font-family: "ExtraBold";
  src: url(./assets/fonts/Galano-Grotesque-Extra-Bold.otf);
}
@font-face {
  font-family: "Medium";
  src: url(./assets/fonts/Galano-Grotesque-Medium.otf);
}
@font-face {
  font-family: "SemiBold";
  src: url(./assets/fonts/Galano-Grotesque-Semi-Bold.otf);
}
@font-face {
  font-family: "Regular";
  src: url(./assets/fonts/Galano-Grotesque.otf);
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
