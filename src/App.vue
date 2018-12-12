<template>
  <div id="app">
    <div id="nav">
      <div id="title-container">
        <h1>Judit Cs. Pacsai</h1>
        <h5>front-end developer</h5>
      </div>
      <div id="nav-links">
        <router-link class="router-link" to="/">home</router-link>
        <router-link class="router-link" to="/about">about</router-link>
        <router-link class="router-link" to="/work">work</router-link>
        <router-link class="router-link" to="/contact">contact</router-link>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss" src="./scss/main.scss"></style>
