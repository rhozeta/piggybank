<template>
  <span>
    <v-navigation-drawer app v-model="drawer" disable-resize-watcher>
      <v-list>
        <template v-for="(item, index) in items">
          <v-list-tile :key="index">
            <v-list-tile-content>{{item.title}}</v-list-tile-content>
          </v-list-tile>
          <v-divider :key="`divider-${index}`"></v-divider>
        </template>
      </v-list>
    </v-navigation-drawer>
    <v-toolbar app color="white lighten-1">
      <v-toolbar-side-icon class="hidden-md-and-up" @click="drawer = !drawer"></v-toolbar-side-icon>
      <v-spacer class="hidden-md-and-up"></v-spacer>
      <v-toolbar-title class="logo">PiggyBank</v-toolbar-title>
      <v-btn flat color="black" class="hidden-sm-and-down">Home</v-btn>
      <v-spacer class="hidden-sm-and-down"></v-spacer>
      <v-btn flat color="black" class="hidden-sm-and-down">SIGN IN</v-btn>
      <v-btn color="#23d806" class="hidden-sm-and-down white--text">JOIN</v-btn>
    </v-toolbar>
  </span>
</template>

<script>
export default {
  name: "AppNavigation",
  data() {
    return {
      appTitle: "PiggyBank",
      drawer: false,
      items: [{ title: "Home" }, { title: "Sign In" }, { title: "Join" }]
    };
  }
};
</script>

<style scoped>
.logo {
  color: #23d806;
}
</style>
