<template>
  <div class='section-margin'>
    <b-container fluid>
      <b-row>
        <b-col xs="12" md="6">
          <h3 class="auto-align">👋🏽 Hi, my name is</h3>
        </b-col>
      </b-row>
      <b-row>
        <b-col xs="12" md="6">
          <div class="title-name auto-align">&#60;Bernard /&#62;</div>
        </b-col>
      </b-row>
      <b-row>
        <b-col xs="12" md="6">
          <p class="auto-align">
            Welcome to my portfolio website. I am a software developer, based in Jakarta, Indonesia. I specialize in creating web application, mobile apps, and UI/UX design.
          </p>
        </b-col>
      </b-row>
      <b-row >
        <b-col>
          <div class="profile-image-introduction">
            <img src="../assets/images/profile-image.png" width="100%"/>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'Introduction',
};
</script>

<style>
@media only screen and (max-width: 768px) {
  .profile-image-introduction{
    margin-top: 100px;
  }
  .title-name{
    font-family: 'Bold';
    font-size: 48px;
    color: #A55BF2;
  }
  .auto-align{
    text-align: center;
  }
}
@media only screen and (min-width: 769px) {
  .profile-image-introduction{
    display: none;
  }
  .title-name{
    font-family: 'Bold';
    font-size: 90px;
    color: #A55BF2;
  }
  .auto-align{
    text-align: left;
  }
}
.section-margin{
  margin: 250px 0;
}
</style>
