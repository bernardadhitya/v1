<template>
  <div class="section-margin">
    <b-container>
      <b-row>
        <b-col>
          <h2 id="featured-header" class="section-title-padding">🔨 What I’ve built</h2>
        </b-col>
      </b-row>
      <b-row v-for="featuredProject in featuredProjects" :key="featuredProject.id">
        <b-col>
          <FeaturedProject
            :id="featuredProject.id"
            :title="featuredProject.title"
            :description="featuredProject.description"
            :tags="featuredProject.tags"
            :thumbnail="featuredProject.thumbnail"
            :link="featuredProject.link"
          />
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
  props: ['featuredProjects'],
};
</script>

<style>
  .section-margin{
    margin: 250px 0;
  }
</style>
