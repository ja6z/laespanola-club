<template>
  <section id="hero" class="hero is-medium">
    <div class="hero-head">
      <b-navbar>
        <template slot="brand">
          <b-navbar-item tag="router-link" :to="{ path: '/' }">
            <h3 class="logo has-text-green is-size-4">La Española</h3>
          </b-navbar-item>
        </template>
        <template slot="end">
          <b-navbar-item tag="div">
            <div class="buttons">
              <a class="a-menu navbar-item"> Inicio </a>
              <a class="a-menu navbar-item"> Fotos </a>
              <a class="a-menu navbar-item"> Contactanos </a>
            </div>
          </b-navbar-item>
        </template>
      </b-navbar>
    </div>
    <div class="hero-body">
      <div class="container">
        <h1 class="has-text-green is-size-1 is-size-3-mobile">
          Complejo Turístico La Española
        </h1>
        <p class="has-text-green">
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum.
        </p>
        <button class="button is-info has-company-bg is-size-7 a-menu">
          Conocenos
        </button>
      </div>
    </div>
  </section>
</template>

<style>
@media (min-width: 1024px) {
  .hero-body {
    /*background-image: url('../../assets/img/gym.svg');*/
    background-size: 30%;
    background-position: 80% 50%;
    background-repeat: no-repeat;
  }
  .hero-body p {
    width: 600px;
  }
}
</style>

<script>
export default {
  name: "Navbar",
};
</script>