<template>
  <div>
    <b-container>
      <b-row>
        <b-col>
          <div
            class="card-wrapper">
            <h4 class="left-align">{{ this.title }}</h4>
            <p class="left-align">{{ this.description }}</p>
            <a :href="this.link">
              <h5 class="right-align color-purple">Go to repository</h5>
            </a>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'OtherProject',
  props: ['title', 'description', 'link'],
};
</script>

<style>
.card-wrapper{
  margin: 24px 0;
  padding: 16px 16px 8px 16px;
  border-radius: 16px;
  box-shadow: 0px 2px 9px 4px rgba(216,216,216,0.5);
  -webkit-box-shadow: 0px 2px 9px 4px rgba(216,216,216,0.5);
  -moz-box-shadow: 0px 2px 9px 4px rgba(216,216,216,0.5);
}
</style>
