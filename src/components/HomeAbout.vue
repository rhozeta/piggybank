<template>
  <div class="about">
    <v-layout row pa-2 wrap>
      <v-flex xs12 sm4 md4 pa-5>
        <v-card>
          <img class="card-icon" src="../assets/plant.png" alt>
          <v-card-title primary-title>
            <div>
              <h3 class="heading mb-1">COMMIT TO THEIR FUTURE</h3>
              <div>Starting early is the only way to be sure that you are financially prepared for your child's future.</div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
      <v-flex xs12 sm4 md4 pa-5>
        <v-card>
          <img class="card-icon" src="../assets/hand.png" alt>
          <v-card-title primary-title>
            <div>
              <h3 class="heading mb-1">MAKE SAVING EASY</h3>
              <div>PiggyBank's awesome features makes it simple to find money to put away.</div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
      <v-flex xs12 sm4 md4 pa-5>
        <v-card>
          <img class="card-icon" src="../assets/heart.png" alt>
          <v-card-title primary-title>
            <div>
              <h3 class="heading mb-1">LET YOUR LOVED ONES INVEST</h3>
              <div>Allow the important people in your life to make a meaningful contribution.</div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
    </v-layout>
  </div>
</template>

<script>
export default {
  name: "HomeAbout"
};
</script>

<style>
.about {
  height: 50vh;
}
.v-card {
  padding: 5%;
  height: 20em;
}
.card-icon {
  height: 8em;
  display: block;
  margin: auto;
  padding-top: 5%;
}
.heading {
  text-align: center;
}
</style>
