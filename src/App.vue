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
@media only screen and (max-width: 768px) {
  #bootstrap-override h1 {
    font-family: 'Bold';
    font-size: 36px;
  }

  #bootstrap-override h2 {
    font-family: 'Bold';
    font-size: 21px;
  }

  #bootstrap-override h3 {
    font-family: 'Bold';
    font-size: 18px;
  }

  #bootstrap-override h4 {
    font-family: 'SemiBold';
    font-size: 18px;
  }

  #bootstrap-override h5 {
    font-family: 'Medium';
    font-size: 14px;
  }

  #bootstrap-override h6 {
    font-family: 'SemiBold';
    font-size: 12px;
  }

  #bootstrap-override p {
    font-family: 'Regular';
    font-size: 16px;
  }
}

@media only screen and (min-width: 769px) {
  #bootstrap-override h1 {
    font-family: 'Bold';
    font-size: 36px;
  }

  #bootstrap-override h2 {
    font-family: 'Bold';
    font-size: 36px;
  }

  #bootstrap-override h3 {
    font-family: 'Bold';
    font-size: 24px;
  }

  #bootstrap-override h4 {
    font-family: 'SemiBold';
    font-size: 18px;
  }

  #bootstrap-override h5 {
    font-family: 'Medium';
    font-size: 14px;
  }

  #bootstrap-override h6 {
    font-family: 'SemiBold';
    font-size: 12px;
  }

  #bootstrap-override p {
    font-family: 'Regular';
    font-size: 16px;
  }
}

.section-title-padding{
  padding-bottom: 30px;
}

.color-purple {
    color: #A55BF2;
}

.left-align {
  text-align: left;
}

.right-align {
  text-align: right;
}
</style>
