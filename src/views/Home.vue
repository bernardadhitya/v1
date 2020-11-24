<template>
  <div class="home">
    <Introduction/>
    <AboutMe/>
    <FeaturedProject/>
    <FeaturedProject/>
    <FeaturedProject/>
  </div>
</template>

<script>
import AboutMe from '../components/AboutMe.vue';
import FeaturedProject from '../components/FeaturedProject.vue';
// @ is an alias to /src
import Introduction from '../components/Introduction.vue';

export default {
  name: 'home',
  components: {
    Introduction,
    AboutMe,
    FeaturedProject,
  },
};
</script>
