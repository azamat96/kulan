<script setup>
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <main>
    <nav class="nav">
      <img class="nav__logo" src="./assets/logo.png">
      <div class="category-btn">
        <img src="./assets/fi_menu.png">
        <span class="category-btn__text">Категории</span>
      </div>
    </nav>
  </main>
</template>

<style>
@import './assets/base.css';
@import "./assets/style.css";

#app {
  font-weight: normal;
  font-family: "Inter";
}
header {
  line-height: 1.5;
}



a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}

@media (min-width: 1024px) {
  body {
    background-color: #E5E5E5;
  }

  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
