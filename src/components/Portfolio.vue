<template>
  <div id="portof">
    <nav>
      <div class="logo">LOGO</div>
      <div class="menu">
        <router-link style="text-decoration: none; padding-right: 80px" to="/"
          >Home</router-link
        >
        <router-link
          style="text-decoration: none; padding-right: 80px"
          to="/about"
          >About</router-link
        >
        <router-link
          style="text-decoration: none; padding-right: 80px"
          to="/project"
          >Project</router-link
        >
        <router-link
          style="text-decoration: none; padding-right: 80px"
          to="/contact"
          >Contact</router-link
        >
        <router-view />
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Portfolio-view",
};
</script>

