<template>
  <div class="navbar-wrapper">
    <b-container>
      <b-row>
        <b-col cols="0" md="6">
          <div></div>
        </b-col>
        <b-col>
          <div class="text-extra-margin">About Me</div>
        </b-col>
        <b-col>
          <div class="text-extra-margin">Featured</div>
        </b-col>
        <b-col>
          <div class="text-extra-margin">Projects</div>
        </b-col>
        <b-col>
          <b-btn variant="outline-primary">Resume</b-btn>
        </b-col>
      </b-row>
    </b-container>
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
}
@media only screen and (min-width: 769px) {
  .text-extra-margin{
    margin-top: 8px;
    font-family: 'SemiBold';
    font-size: 18px;
  }
}
</style>
