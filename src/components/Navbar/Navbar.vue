<template>
  <div class="wrapper">
    <div class="nav">
      <router-link to="/" class="hoverable">
        ahmad<b>fahmi</b>
      </router-link>
      <div class="menu">
        <router-link to="/">
          profile
        </router-link>
        <router-link to="/">
          resume
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style lang="scss" scoped>
.nav {
  @include page;
  padding: 1.5rem 0;
  display: flex;
  justify-content: space-between;
  @include mobile {
    padding-top: 1rem;
    padding-bottom: 1rem;
  }
}

a {
  font-size: 1.1rem;
  color: black;
  font-family: 'Noticia Text', serif;
  @include mobile {
    font-size: 0.85rem;
  }
}

.menu > a {
  margin-left: 2rem;
  @include mobile {
    margin-left: 1.1rem;
  }
}
</style>