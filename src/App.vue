<template>
  <div id="app">
    <div id="nav">
      <img src="./assets/images/logo-blog.png" alt="Blog">
      <router-link to="/">Home</router-link> 
      <router-link to="/about">Sobre</router-link>
      <router-link to="/">Categoria</router-link> 
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
@import './assets/scss/main';
</style>
