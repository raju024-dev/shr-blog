<template>
  <div id="app">
    <Navbar />
    <b-container>
      <b-row>
        <b-col lg="8">
          <router-view />
        </b-col>
        <b-col lg="4">
          <Sidebar />
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<style>
body{
  min-height: 1000px;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>

<script>
import Navbar from "./components/Navbar.vue";
import Sidebar from "./components/Sidebar.vue";
export default {
  components: {
    Navbar,
    Sidebar
  },
};
</script>
