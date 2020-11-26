<template>
  <div>
    <b-container>
      <b-row>
        <b-col cols="12" md="5">
          <div class="image-wrapper">
            <img :src="require(`../assets/images/${this.thumbnail}`)" width="100%"/>
          </div>
        </b-col>
        <b-col cols="2" md="1">
          <div class="featured-project-number color-purple">{{ this.id }}</div>
          <div class="purple-line"></div>
        </b-col>
        <b-col cols="10" md="6">
          <b-row>
            <b-col>
              <h5 class="color-purple left-align">Featured Project</h5>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h1 class="left-align">{{ this.title }}</h1>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <div class="card-wrapper">
                <p class="left-align">
                  {{ this.description }}
                </p>
              </div>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h6 class="right-align">Techs used:</h6>
              <p class="color-purple right-align">{{ this.tags.join(', ') }}</p>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <div class="button-wrapper">
                <b-btn variant="outline-primary">Go to repository</b-btn>
              </div>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'FeaturedProject',
  props: ['id', 'title', 'description', 'tags', 'thumbnail'],
};
</script>

<style>
  .featured-project-number{
    font-family: 'Regular';
    font-size: 36px;
  }
  .card-wrapper{
    margin: 24px 0;
    padding: 16px 16px 8px 16px;
    border-radius: 16px;
    box-shadow: 0px 2px 9px 4px rgba(216,216,216,0.5);
    -webkit-box-shadow: 0px 2px 9px 4px rgba(216,216,216,0.5);
    -moz-box-shadow: 0px 2px 9px 4px rgba(216,216,216,0.5);
  }
  .image-wrapper{
    margin: 24px 0;
    object-fit: contain;
  }
  .button-wrapper{
    text-align: right;
    margin-bottom: 40px;
  }
  .purple-line{
    background: linear-gradient(
      180deg,
      rgba(165,91,242,1) 0%,
      rgba(165,91,242,0.5) 50%,
      rgba(255,255,255,0) 100%
    );
    width: 3px;
    height: 75%;
    margin: 0 21px;
  }
</style>
