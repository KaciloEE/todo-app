<template>
  <header>
    <nav>
      <nuxt-link to="/home">Home</nuxt-link>
      <nuxt-link to="/about">About</nuxt-link>
    </nav>
  </header>
  <NuxtPage />
</template>

<style>
nav {
  display: flex;
  gap: 15px;
}
</style>
