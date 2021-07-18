<template>
  <div class="hello">
    <b-container>
      <b-row>
        <h1>{{ msg }}</h1>
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
</style>
