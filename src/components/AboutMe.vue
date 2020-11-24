<template>
  <div class='section-margin'>
    <b-container fluid>
      <b-row>
        <b-col>
          <h3>👀 About me</h3>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <p>
            Hi! My name is Bernard, I’m a software engineer based in Jakarta, Indonesia.
          </p>
          <p>
            Thorough my journey, I’ve competed at various coding competitions; competitive programming and hackathons. I’ve aslo became a part-time teacher at a coding school for kids, and an intern at a bank in Indonesia.
          </p>
          <p>
            Here are some technologies I’ve used in my journey;
          </p>
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
  h3{
    font-family: 'Bold';
    font-size: 21px !important;
  }
  p{
    font-family: 'Regular';
    font-size: 16px !important;
  }
  .section-margin{
    margin: 250px 0;
  }
</style>
