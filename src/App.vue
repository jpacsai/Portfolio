<template>
  <div id="app">
    <div id="nav">
      <div>Judit Cs. Pacsai</div>
      <div id="nav-links">
        <router-link class="router-link" to="/">Home</router-link>
        <router-link class="router-link" to="/about">About</router-link>
        <router-link class="router-link" to="/work">Work</router-link>
        <router-link class="router-link" to="/contact">Contact</router-link>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss" src="./scss/main.scss"></style>
