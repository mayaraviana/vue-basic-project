<template>
  <div class="hello">
    <b-container>
      <b-row>
        <h1 class="home-msg">{{ msg }}</h1>
      </b-row>
      <b-row>
        <b-col cols="12" md="4">col</b-col>
        <b-col cols="6" md="4">col</b-col>
        <b-col cols="6" md="4">col</b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-msg {
  font-size: 2.5em;
}
@media (min-width: 900px) {
  .home-msg {
    font-size: 4em;
  }
}
</style>
