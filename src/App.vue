<script setup>
import PlaceHolder from './components/Placeholder.vue'

</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/triplesept.png" width="50" height="50" />
    <div class="wrapper">
      <PlaceHolder msg=".triplesept"></PlaceHolder>
    </div>
  </header>

  <main>
    <a href="https://drive.google.com/drive/u/1/folders/1g5j4EW0VG0LOHraaFsoOEoL4YLr7nKOX">
    <div class="button1" alt="team's cloud.">
    </div>
    </a>
  </main>
</template>

<style scoped>
header {
  line-height: 1;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}
.button1 {
  display: flex;
  margin: 1rem auto;
  line-height: 13;
  background-color: #f2f2f2;
  color: #f2f2f2;
  width: 100px;
  height: 100px;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
