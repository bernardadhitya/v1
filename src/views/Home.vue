<template>
  <div id="bootstrap-override" class="fluid-padding">
    <Navbar/>
    <Introduction/>
    <AboutMe/>
    <FeaturedProjects :featuredProjects="featuredProjects"/>
    <OtherProjects :otherProjects="otherProjects"/>
  </div>
</template>

<style>
@media only screen and (max-width: 768px) {
  .fluid-padding{
    padding: 0 24px;
  }
}
@media only screen and (min-width: 769px) {
  .fluid-padding{
    padding: 0 80px;
  }
}
</style>

<script>
import Navbar from '../components/Navbar.vue';
import AboutMe from '../components/AboutMe.vue';
import FeaturedProjects from '../components/FeaturedProjects.vue';
import Introduction from '../components/Introduction.vue';
import OtherProjects from '../components/OtherProjects.vue';
import featuredProjectsList from '../constants/FeaturedProjects';
import otherProjectsList from '../constants/OtherProjects';

export default {
  name: 'home',
  data() {
    return {
      featuredProjects: [],
      otherProjects: [],
    };
  },
  async created() {
    this.featuredProjects = featuredProjectsList;
    this.otherProjects = otherProjectsList;
  },
  components: {
    Navbar,
    Introduction,
    AboutMe,
    FeaturedProjects,
    OtherProjects,
  },
};
</script>
