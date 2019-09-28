<template>
  <div class="home page">
    <div class="header">
      <h1>frontend & ui/ux <span>enthusiast</span><br>self-claimed <i>hackathlete</i><br>based in Bandung, ID_</h1>
      <p>Tech geek, but designer by heart.</p>
      <p>
        Former Software Engineer Intern at
        <a href="https://www.blibli.com">Blibli</a> and
        <a href="http://mapan.id">Mapan</a>.
      </p>
      <p>In love with web development.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style lang="scss" scoped>
.header > h1 {
  font-family: 'Noticia Text', serif;
  font-size: 2.25rem;
  margin-bottom: 2rem;
  span { color: $blue; }
  @include mobile {
    font-size: 4.5vh;
  }
}

.header > p {
  font-size: 1.1rem;
  line-height: 1.8rem;
  a {
    font-weight: bold;
    color: $blue;
  }
  @include mobile {
    font-size: 2.25vh;
    line-height: 3.5vh;
  }
}
</style>
