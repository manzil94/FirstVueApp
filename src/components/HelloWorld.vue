<template>
      <div>
    <h1> The athlete model </h1>
    <div>My name is {{name}}</div>
        </div>
</template>>

<script>
export default {
    props: {
        name: { type: String, default: "Manzil" }
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
h1 {
  list-style-type: none;
  padding: 2;
}
h2 {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
