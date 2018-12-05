<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Liens essentiels</h2>
    <ul>
      <li>
        <a
          href="https://www.youtube.com/watch?v=d8p_Dw5BqZw"
          target="_blank"
        >
          Lien du film
        </a>
      </li>
      <li>

      </li>


      <br>
      <li>

      </li>
    </ul>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Les acteurs'
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
