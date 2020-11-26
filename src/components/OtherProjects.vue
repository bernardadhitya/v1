<template>
  <div class="others-section-margin">
    <b-container>
      <b-row>
        <b-col>
          <h2 id="other-header" class="section-title-padding">🛠 More things I’ve built</h2>
        </b-col>
      </b-row>
      <b-row>
        <b-col cols="12" md="4" v-for="otherProject in otherProjects" :key="otherProject.id">
          <OtherProject
            :title="otherProject.title"
            :description="otherProject.description"
            :link="otherProject.link"
          />
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import OtherProject from './OtherProject.vue';

export default {
  name: 'OtherProjects',
  components: { OtherProject },
  props: ['otherProjects'],
};
</script>

<style>
.others-section-margin{
  margin-bottom: 100px
}
</style>
