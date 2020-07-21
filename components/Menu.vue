<template>
  <b-navbar toggleable="lg" fixed="top">
    <b-navbar-brand to="/">
      <div class="d-flex flex-row align-items-center justify-content-start">
        <img class="d-none d-lg-block mr-2" src="~/assets/images/logo.png" alt="Website Logo">
        <div class="d-flex flex-column align-items-start justify-content-center">
          <h1 class="mb-0">
            KEVINLim.NET
          </h1>
          <p class="mb-0 text-muted">
            Auckland Based Web Developer
          </p>
        </div>
      </div>
    </b-navbar-brand>
    <b-navbar-toggle target="nav-collapse" />
    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item class="px-3" to="/projects">
          <h3>Projects</h3>
        </b-nav-item>
        <b-nav-item class="px-3" to="/contact">
          <h3>Contact</h3>
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<style lang="scss" scoped>
  #nav-collapse {
    @media (max-width: 991px) {
      background: #f7f8fb;
    }
  }

  .navbar-brand {
    @media (max-width: 991px) {
      font-size: rfs(1rem);
    }
  }

  .navbar-toggler {
    border: none;
  }
</style>
