<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <router-link :to="{ name: 'dashboard' }" class="navbar-brand mx-3"
      >LARAVEL PASSPORT + VUE</router-link
    >
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav mx-3">
        <li class="nav-item">
          <router-link :to="{ name: 'register' }" class="nav-link" href=""
            >REGISTER</router-link
          >
        </li>
        <li class="nav-item">
          <router-link :to="{ name: 'login' }" class="nav-link" href="#"
            >LOGIN</router-link
          >
        </li>
      </ul>
    </div>
  </nav>
</template>
<script>
export default { name: "myNavbar" };
</script>