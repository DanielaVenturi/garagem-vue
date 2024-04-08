import router from './router';
<template>
  <header>
    <router-link :to="{ name: 'home' }">Home</router-link> |
    <router-link to="/categorias">Categorias</router-link> |
    <router-link to="/acessorios">Acessorio</router-link> |
    <router-link to="/cores">Cor</router-link>|
    <router-link to="/marcas">Marcas</router-link>
  </header>
  <main>
    <RouterView />
  </main>
</template>
