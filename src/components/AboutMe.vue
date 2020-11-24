<template>
  <div class='section-margin'>
    <b-container fluid>
      <b-row>
        <b-col xs="12" md="6">
          <h2 class="section-title-padding auto-align">👀 About me</h2>
        </b-col>
      </b-row>
      <b-row>
        <b-col xs="12" md="6">
          <p class="auto-align">
            Hi! My name is Bernard, I’m a software engineer based in Jakarta, Indonesia.
          </p>
          <p class="auto-align">
            Thorough my journey, I’ve competed at various coding competitions; competitive programming and hackathons. I’ve aslo became a part-time teacher at a coding school for kids, and an intern at a bank in Indonesia.
          </p>
          <p class="auto-align">
            Here are some technologies I’ve used in my journey;
          </p>
        </b-col>
      </b-row>
      <b-row>
        <b-col xs="12" md="6">
          <div class="skills-logo-image-wrapper">
            <img src="../assets/images/skills-logo.png"/>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'AboutMe',
};
</script>

<style>
  .section-margin{
    margin: 250px 0;
  }
  @media only screen and (max-width: 768px) {
    .skills-logo-image-wrapper img{
      width: 100%;
    }
    .auto-align{
      text-align: center;
    }
  }
  @media only screen and (min-width: 769px) {
    .skills-logo-image-wrapper img{
      width: 60%;
    }
    .auto-align{
      text-align: left;
    }
  }
</style>
