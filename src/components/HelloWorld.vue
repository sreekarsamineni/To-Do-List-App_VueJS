<template>
  <div id="app">
    <ul>
      <li><a href=""></a>Home</li>
      <li><a href=""></a>Projects</li>
      <li><a href=""></a>Dashboard</li>
      <li><a href=""></a>Create</li>
    </ul>
  
  </div>
</template>

<script>
export default {

}
</script>

<style>

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color:black;
  font-size: 24px;
  height: 100vh;
}

.flex-center{
  display: flex;
  justify-content: center;
 }

.nav {
  display: flex;
  list-style: none;
  padding: 15px 0;
  margin: 0;
  justify-content: flex-end;
  background: blue;
  border-bottom: 1px solid lightgray;
  margin-bottom: 24px;
}

.nav a {
  color: #636b6f;
  padding: 0 25px;
  font-size: 14px;
  font-weight: 600;
  letter-spacing: .1rem;
  text-decoration: none;
  text-transform: uppercase;
} 
</style>