<template>
    <header>
        <nav>
            <button class="burger-menu"></button>
        <figure class="header-logo"> <img src="assets/images/logo.png" alt=""></figure>
        <div class="wrapper-basket-and-lupa">
            <figure><img src="assets/images/lupa.png" alt=" "></figure>
            <button @click="toggleSidebar"></button>
        </div>
        </nav>
        <sidebar v-if="showSidebar"/>    
    </header>
  

</template>

<script>
export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>


