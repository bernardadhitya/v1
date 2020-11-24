<template>
  <div class="navbar-wrapper">
    <b-container>
      <b-row>
        <b-col cols="0" md="6">
          <div></div>
        </b-col>
        <b-col>
          <h4 class="text-extra-margin">About Me</h4>
        </b-col>
        <b-col>
          <h4 class="text-extra-margin">Featured</h4>
        </b-col>
        <b-col>
          <h4 class="text-extra-margin">Projects</h4>
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
.text-extra-margin{
  margin-top: 8px;
}
</style>
