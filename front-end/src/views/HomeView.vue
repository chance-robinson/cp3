<template>
  <div class="home">
    <div class="container intro">
    <div class="row">
      <div class="col-4">
        <h2>Resume</h2>
        <img class="img-fluid" src="/images/miniresume.PNG" alt="">
      </div>
      <div class="col-4">
        <h2>Experience</h2>
        <ul>
          <li>Walgreens</li>
          <li>Low Power Voltage Systems</li>
          <li>Entrepenuer</li>
          <li>Programmer</li>
        </ul>
      </div>
      <div class="col-4">
        <h2>Projects</h2>
        <ul>
          <li>Evil Hangman</li>
          <li>SpellChecker</li>
          <li>3D Maze</li>
          <li>Code Breaker</li>
          <li><a href="http://3b.chancerobinson.xyz/">Fake Grocery Store</a></li>
        </ul>
      </div>
    </div>
  </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style scoped>
.home {
  margin-top: 3rem;
}
</style>
