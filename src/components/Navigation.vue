<template>
  <div>
    <b-container>
      <b-row>
        <b-navbar toggleable="lg" type="light">
          <b-navbar-brand to="/">NavBar</b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="ml-auto">
              <b-nav-item to="/">Home</b-nav-item>
              <b-nav-item to="/about">About</b-nav-item>
              <b-nav-item to="/" disabled>Disabled</b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'Navigation'
};
</script>

<style>
.ml-auto {
  margin-left: auto;
}
</style>
