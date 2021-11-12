<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Nuxt SSR </a>
       
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav me-auto">
          <li class="nav-item">
            <nuxt-link class="nav-link" exact no-prefetch active-class="active" to="/">Home</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" active-class="active" to="/about">About</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" active-class="active" to="/users">Users</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" active-class="active" to="/login">Login</nuxt-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>