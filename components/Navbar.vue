<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <nuxt-link class="navbar-brand" to="/">
      <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="30" height="30" alt="logo">
    </nuxt-link>
    <nuxt-link class="navbar-brand" to="/">
      <img src="https://nuxtjs.org/logos/nuxt-square-white.svg" width="30" height="30" alt="logo">
    </nuxt-link>
    <button class="navbar-toggler" type="button" data-toggle="collapse"
            data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <nuxt-link class="nav-link" to="/">Главная</nuxt-link>
        </li>
        <li class="nav-item ">
          <nuxt-link class="nav-link" to="/contact">Контакты</nuxt-link>
        </li>
      </ul>
      <span class="navbar-text mr-2">Username</span>
      <nuxt-link class="btn btn-outline-light mr-2" to="/signout">Выход</nuxt-link>
      <nuxt-link class="btn btn-outline-light mr-2" to="/signin">Вход</nuxt-link>
      <nuxt-link class="btn btn-outline-light mr-2" to="/signup">Регистрация</nuxt-link>
    </div>
  </nav>
</template>

<style scoped>

</style>
