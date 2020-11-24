<template>
  <div id="bootstrap-override" class="fluid-padding">
    <Introduction/>
    <AboutMe/>
    <FeaturedProjects/>
    <OtherProjects/>
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
    padding: 0 60px;
  }
}
</style>

<script>
import AboutMe from '../components/AboutMe.vue';
import FeaturedProjects from '../components/FeaturedProjects.vue';
import Introduction from '../components/Introduction.vue';
import OtherProjects from '../components/OtherProjects.vue';

export default {
  name: 'home',
  components: {
    Introduction,
    AboutMe,
    FeaturedProjects,
    OtherProjects,
  },
};
</script>
