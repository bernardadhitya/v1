<template>
  <div class='title-section-margin'>
    <b-container fluid>
      <b-row align-h="center">
        <b-col xs="12" md="5">
          <b-row>
            <b-col cols="12">
              <h3 id="intro-header" class="auto-align-intro">👋🏽 Hi, my name is</h3>
            </b-col>
            <b-col xs="12">
              <div class="title-name auto-align-intro">&#60;Bernard /&#62;</div>
            </b-col>
          </b-row>
          <b-row>
            <b-col xs="12" md="10">
              <p class="auto-align-intro">
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
        </b-col>
        <b-col xs="12" md="4">
          <div class="profile-image-introduction">
            <img src="../assets/images/profile-picture.png" width="100%"/>
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
    margin: 150px 0;
  }
  .profile-image-introduction{
    margin-top: 50px;
  }
  .title-name{
    font-family: 'Bold';
    font-size: 48px;
    color: #A55BF2;
  }
  .auto-align-intro{
    text-align: center;
  }
}
@media only screen and (min-width: 769px) {
  .title-section-margin{
    margin: 200px 0;
  }
  .title-name{
    font-family: 'Bold';
    font-size: 64px;
    color: #A55BF2;
  }
  .auto-align-intro{
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
