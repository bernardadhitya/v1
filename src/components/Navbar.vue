<template>
  <div class="navbar-wrapper">
    <scrollactive class="my-nav" :offset="150">
      <a href="#intro-header" class="scrollactive-item">Intro</a>
      <a href="#about-header" class="scrollactive-item">About me</a>
      <a href="#featured-header" class="scrollactive-item">Featured</a>
      <a href="#other-header" class="scrollactive-item">Projects</a>
    </scrollactive>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>

<style>
.navbar-wrapper{
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  padding: 20px;
  z-index: 10;
  background-color: white;
  align-content: right;
  box-shadow: 0px 2px 9px 4px rgba(216,216,216,0.5);
  -webkit-box-shadow: 0px 2px 9px 4px rgba(216,216,216,0.5);
  -moz-box-shadow: 0px 2px 9px 4px rgba(216,216,216,0.5);
}
@media only screen and (max-width: 768px) {
  .text-extra-margin{
    margin-top: 12px;
    font-family: 'SemiBold';
    font-size: 12px;
  }
  .my-nav{
    text-align: center;
  }
}
@media only screen and (min-width: 769px) {
  .text-extra-margin{
    margin-top: 8px;
    font-family: 'SemiBold';
    font-size: 18px;
  }
  .my-nav{
    text-align: right;
  }
}

.scrollactive-item{
  margin: 0 10px;
  font-family: 'SemiBold';
  color: #323232;
}
</style>
