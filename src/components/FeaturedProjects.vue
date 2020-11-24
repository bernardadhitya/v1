<template>
  <div class="section-margin">
    <b-container>
      <b-row>
        <b-col>
          <h2>🔨 What I’ve built</h2>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <FeaturedProject/>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <FeaturedProject/>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <FeaturedProject/>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import FeaturedProject from './FeaturedProject.vue';

export default {
  name: 'FeaturedProjects',
  components: { FeaturedProject },
};
</script>

<style>
  h2{
    font-family: 'Bold';
    font-size: 21px !important;
  }
  .section-margin{
    margin: 250px 0;
  }
</style>
