<template>
  <span>
    <home-hero></home-hero>
    <home-about></home-about>
  </span>
</template>

<script>
import HomeHero from "../components/HomeHero";
import HomeAbout from "../components/HomeAbout";
export default {
  components: {
    HomeHero,
    HomeAbout
  }
};
</script>
