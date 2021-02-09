<template>
  <div class="home">
    <div
      class="p-5 text-center bg-image"
      style="
      background-image: url('https://images.unsplash.com/photo-1498837167922-ddd27525d352?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80');
      height: 500px;
    "
    >
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <div class="text-white">
            <h1 class="mb-3">FoodTV</h1>
            <h4 class="mb-3">Fresh Food Served Daily</h4>
            <a
              class="btn btn-outline-light btn-lg"
              href="mailto:krammer439298@gmail.com"
              role="button"
              >Learn More</a
            >
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <br />
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem
          consequuntur maiores maxime ab architecto quasi, quas excepturi quae
          accusamus eum illum totam rerum? Molestias in cupiditate magni
          doloribus provident? Libero. <br />
          <img
            src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80"
            alt="food"
            class="img-fluid"
            width="100%"
          />
        </div>
        <div class="col-md-4">
          <div class="intro-img">
            <h1>Calling All Chefs!!!</h1>
          </div>
        </div>
        <div class="col-md-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem
          consequuntur maiores maxime ab architecto quasi, quas excepturi quae
          accusamus eum illum totam rerum? Molestias in cupiditate magni
          doloribus provident? Libero. <br />
          <img
            src="https://images.unsplash.com/photo-1493770348161-369560ae357d?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            alt="food"
            class="img-fluid"
            width="100%"
          />
        </div>
      </div>
    </div>
    <HelloWorld />
    <br /><br />
    <div class="container">
      <div class="row">
        <div class="col-md-6 text-center content-text">
          <h1 class="display-4">Dinner Parties Welcomed</h1>
          <br />
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque maiores
          aperiam explicabo nihil laboriosam ipsa cumque. Similique hic, at
          animi suscipit est maiores sunt perspiciatis, ab totam labore, commodi
          distinctio! Lorem ipsum, dolor sit amet consectetur adipisicing elit.
          Maxime necessitatibus suscipit corrupti! Molestias ipsum eveniet omnis
          sit modi atque itaque error rerum illo reprehenderit! Cum laudantium
          qui totam facere distinctio. Lorem ipsum, dolor sit amet consectetur
          adipisicing elit. Facilis illo aliquid in aspernatur? Quae sed dicta
          nisi necessitatibus commodi accusantium, nam quasi, cum repellendus a,
          incidunt reiciendis est saepe distinctio!
        </div>
        <br />
        <div class="col-md-6">
          <img
            src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            alt=""
            class="img-fluid"
            width="100%"
          />
        </div>
      </div>
    </div>
    <br /><br />
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <img
            src="https://images.unsplash.com/photo-1499028344343-cd173ffc68a9?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            alt=""
            class="img-fluid"
            width="100%"
          />
        </div>
        <div class="col-md-6 text-center content-text">
          <h1 class="display-4">We Are Second To None</h1>
          <br />
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque maiores
          aperiam explicabo nihil laboriosam ipsa cumque. Similique hic, at
          animi suscipit est maiores sunt perspiciatis, ab totam labore, commodi
          distinctio! Lorem ipsum, dolor sit amet consectetur adipisicing elit.
          Maxime necessitatibus suscipit corrupti! Molestias ipsum eveniet omnis
          sit modi atque itaque error rerum illo reprehenderit! Cum laudantium
          qui totam facere distinctio. Lorem ipsum, dolor sit amet consectetur
          adipisicing elit. Facilis illo aliquid in aspernatur? Quae sed dicta
          nisi necessitatibus commodi accusantium, nam quasi, cum repellendus a,
          incidunt reiciendis est saepe distinctio!
        </div>
      </div>
    </div>
    <br /><br />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style scoped style lang="scss">
.intro-img {
  background: url(https://images.unsplash.com/photo-1611657365907-1ca5d9799f59?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  width: 100%;
  height: auto;
  padding-top: 50%;
  padding-bottom: 50%;
  color: white !important;
}
.content-text {
  padding-top: 20px;
}
</style>
