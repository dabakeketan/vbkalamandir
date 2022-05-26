<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
   <nav class="navbar navbar-expand-lg navbar-dark bg-custom">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">VB Kalamandir</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
           <RouterLink class="" to="/">Home</RouterLink>
        </li>
        <li class="nav-item">
           <RouterLink to="/about" class="">About</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink to="/gallery" class="">Gallery</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink to="/contact" class="">Contact</RouterLink>
        </li>
      </ul>
    </div>
  </div>
</nav>
  </header>

  <RouterView />
</template>

<style>
@import "@/assets/base.css";
.bg-custom {
  background: #ffc107;
}
nav {
  margin: 0 !important;
}


nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

#app {
  padding-bottom: 20px;
  font-weight: normal;
}

header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: #ffffff;
  font-weight: bold;
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
  color: #444;
  font-size: 14px;
  font-weight: bold;
}

nav a:hover {
  color: #fff;
  background: transparent;
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  
}
</style>
