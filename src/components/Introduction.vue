<template>
  <div class='section-margin'>
    <b-container fluid>
      <b-row>
        <b-col>
          <h4>👋🏽 Hi, my name is</h4>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <h1>&#60;Bernard /&#62;</h1>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <p>
            Welcome to my portfolio website. I am a software developer, based in Jakarta, Indonesia. I specialize in creating web application, mobile apps, and UI/UX design.
          </p>
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
  .section-margin{
    margin: 250px 0;
  }
  h1{
    font-family: 'Bold';
    font-size: 60px !important;
    color: #A55BF2;
  }
  h4{
    font-family: 'Bold';
    font-size: 18px !important;
  }
  p{
    font-family: 'Regular';
    font-size: 16px !important;
  }
</style>
