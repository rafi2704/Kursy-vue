<!-- src/App.vue -->
<template>
  <div id="app">
    <header>
      <h1>Moja Strona w Vue</h1>
      <nav>
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/about">About</router-link></li>
          <li><router-link to="/contact">Contact</router-link></li>
        </ul>
      </nav>
    </header>
    <main>
      <router-view></router-view>
    </main>
    <footer>
      <p>&copy; 2025 Moja Strona</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style scoped>
#app {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  color: #333;
  margin: 0;
  padding: 20px;
}

header {
  background-color: #4CAF50;
  color: white;
  padding: 20px;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav li {
  display: inline-block;
  margin-right: 10px;
}

main {
  margin-top: 20px;
}

footer {
  text-align: center;
  margin-top: 20px;
}
</style>
