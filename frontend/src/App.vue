<template>
  <div class="container">
    <h3 class="d-flex justify-content-center">Vue JS Front End</h3>
    <h5 class="d-flex justify-content-center">Employee Management Portal</h5>

    <nav class="navbar navbar-expand-sm bg-light navbar-dark">
      <ul class="navbar-nav">
        <li class="nav-item m-1">
          <router-link class="btn btn-light btn-outline-primary" to="/"
            >Home</router-link
          >
        </li>

        <li class="nav-item m-1">
          <router-link class="btn btn-light btn-outline-primary" to="/employee"
            >Employee</router-link
          >
        </li>
      </ul>
    </nav>
    <router-view></router-view>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
