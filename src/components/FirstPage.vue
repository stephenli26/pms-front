<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <!--<h2>Vue first page for PMS</h2> -->
    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
        >
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'FirstPage',
  data () {
    return {
      msg: 'PMS project staging tes for 2019-11-16 20:29'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
