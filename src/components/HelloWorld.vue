<template>
  <div class="container">
    <br /><br /><br /><br />
    <h1 class="text-center display-4">Glorious Food Options</h1>
    <br /><br />
    <!-- Carousel wrapper -->
    <div
      id="carouselBasicExample"
      class="carousel slide carousel-fade"
      data-mdb-ride="carousel"
    >
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li
          data-mdb-target="#carouselBasicExample"
          data-mdb-slide-to="0"
          class="active"
        ></li>
        <li data-mdb-target="#carouselBasicExample" data-mdb-slide-to="1"></li>
        <li data-mdb-target="#carouselBasicExample" data-mdb-slide-to="2"></li>
      </ol>

      <!-- Inner -->
      <div class="carousel-inner">
        <!-- Single item -->
        <div class="carousel-item active">
          <img
            src="https://images.unsplash.com/photo-1504754524776-8f4f37790ca0?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            class="d-block max w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h2>Breakfast</h2>
            <p>Our Endless Option Menu Will Keep You Reading</p>
          </div>
        </div>

        <!-- Single item -->
        <div class="carousel-item">
          <img
            src="https://images.unsplash.com/photo-1476224203421-9ac39bcb3327?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            class="d-block max w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h2>Lunch Choices</h2>
            <p>Freshly Served and Always Made At Order Time</p>
          </div>
        </div>

        <!-- Single item -->
        <div class="carousel-item">
          <img
            src="https://images.unsplash.com/photo-1455619452474-d2be8b1e70cd?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            class="d-block max w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h2>Fabulous Soups</h2>
            <p>Our Soups of the Day Will Take Your Breath Away</p>
          </div>
        </div>
      </div>
    </div>
    <!-- Inner -->

    <!-- Controls -->
    <a
      class="carousel-control-prev"
      href="#carouselBasicExample"
      role="button"
      data-mdb-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </a>
    <a
      class="carousel-control-next"
      href="#carouselBasicExample"
      role="button"
      data-mdb-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </a>
  </div>
  <!-- Carousel wrapper -->
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String
  }
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.max {
  max-height: 550px !important;
}
</style>
