<template>
  <v-container fluid class="home-hero-bg">
    <v-container class="home-hero">
      <v-layout row pa-5 justify-center align-center wrap>
        <v-flex class="iphone-container" fill-height block xs12 sm6 md6 text-xs-center>
          <img class="hero-iphone" src="../assets/growth.png" alt>
        </v-flex>
        <v-flex block xs12 sm6 md6 text-xs-center>
          <v-card class="hero-card">
            <v-container fill-height fluid>
              <div>
                <div class="display-1 font-weight-bold mb-3">Start saving today.</div>
                <div
                  class="font-weight-bold"
                >PiggyBank is the easiest way to let your loved ones support your new family.</div>
                <v-btn color="#23d806" class="hidden-sm-and-down white--text mt-3">Get Started</v-btn>
              </div>
            </v-container>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>
  </v-container>
</template>

<script>
export default {
  name: "HomeHero"
};
</script>

<style scoped>
.home-hero {
  max-height: max-content;
}
.home-hero-bg {
  background-image: url("../assets/pattern.png");

  /* Set a specific height */
  height: max-content;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.hero-card {
  border-radius: 10px;
  height: max-content;
}
.hero-iphone {
  height: 13em;
}
</style>