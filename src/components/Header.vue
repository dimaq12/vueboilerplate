<template>
  <header class="header">
    <div class="container">
      <nav>
          <router-link class="button is-primary" to="/" @click.native="open = false">
            Posts
          </router-link>
          <a class="button is-info" href="https://foreignrap.com/" @click="open = false">
            Foreignrap
          </a>
      </nav>
    </div>
  </header>
</template>