<template>
  <div class="home">
    <Introduction/>
    <AboutMe/>
    <FeaturedProjects/>
  </div>
</template>

<script>
import AboutMe from '../components/AboutMe.vue';
import FeaturedProjects from '../components/FeaturedProjects.vue';
// @ is an alias to /src
import Introduction from '../components/Introduction.vue';

export default {
  name: 'home',
  components: {
    Introduction,
    AboutMe,
    FeaturedProjects,
  },
};
</script>
