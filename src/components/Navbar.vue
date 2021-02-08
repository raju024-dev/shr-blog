<template>
  <div>
    <b-navbar 
    sticky
    fluid
    toggleable="lg" type="dark" variant="dark">
      <b-container>
        <router-link :to="{ name: 'Home' }">
          <b-navbar-brand>SHR Blog</b-navbar-brand>
        </router-link>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <router-link :to="{ name: 'Home' }">Home</router-link>
            <router-link :to="{ name: 'About' }">About
            </router-link>
            <router-link :to="{ name: 'Services' }">Services</router-link>
            <router-link :to="{ name: 'Contact' }">Contact</router-link>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>
  </div>
</template>

<script>
export default {
  
};
</script>

<style>
.navbar-nav{
  display: relative;
  margin-left: auto;
}
.navbar-nav a{
  display: block;
  color: #bbb;
  margin: 5px 10px;
  text-decoration: none;
}
.navbar-nav a.router-link-exact-active{
  color: white;
}

</style>

