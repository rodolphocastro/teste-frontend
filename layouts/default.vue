<template>
  <div>
    <header>
      <navbar></navbar>
    </header>
    <main>
      <nuxt />
    </main>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'

export default {
  components: {
    Navbar
  }
}

</script>

<style>

html{
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

main {
  padding-top: 1rem;
}

</style>
