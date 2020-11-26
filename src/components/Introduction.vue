<template>
  <div class='title-section-margin'>
    <b-container fluid>
      <b-row>
        <b-col xs="12" md="6">
          <h3 id="intro-header" class="auto-align">👋🏽 Hi, my name is</h3>
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
      <b-row>
        <b-col class="icons-wrapper">
          <a href="https://github.com/bernardadhitya">
            <img src="../assets/images/github-icon.png"/>
          </a>
          <a href="https://www.linkedin.com/in/bernard-adhitya-k-a98618144/">
            <img src="../assets/images/linkedin-icon.png"/>
          </a>
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
  .title-section-margin{
    margin: 150px 0 250px 0;
  }
  .profile-image-introduction{
    margin-top: 50px;
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
  .title-section-margin{
    margin: 225px 0;
  }
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
  .icons-wrapper{
    text-align: left;
  }
}
.icons-wrapper img{
  padding: 10px;
}
</style>
