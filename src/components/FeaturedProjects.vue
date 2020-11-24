<template>
  <div class="section-margin">
    <b-container>
      <b-row>
        <b-col>
          <h2 id="featured-header" class="section-title-padding">🔨 What I’ve built</h2>
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
  .section-margin{
    margin: 250px 0;
  }
</style>
