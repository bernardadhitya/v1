<template>
  <div class="section-margin">
    <b-container>
      <b-row>
        <b-col>
          <h2 id="other-header" class="section-title-padding">🛠 More things I’ve built</h2>
        </b-col>
      </b-row>
      <b-row>
        <b-col cols="12" md="4">
          <OtherProject/>
        </b-col>
        <b-col cols="12" md="4">
          <OtherProject/>
        </b-col>
        <b-col cols="12" md="4">
          <OtherProject/>
        </b-col>
        <b-col cols="12" md="4">
          <OtherProject/>
        </b-col>
        <b-col cols="12" md="4">
          <OtherProject/>
        </b-col>
        <b-col cols="12" md="4">
          <OtherProject/>
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
}
</script>

<style>

</style>