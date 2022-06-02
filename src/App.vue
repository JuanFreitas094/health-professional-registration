<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <router-view/>
</template>

<script>
</script>

<style>
body{
  background-color: #ffe766;
}

.main-title {
  font-family: 'Comfortaa', cursive;
  color: #483698;
} 

.btn-primary {
  background-color: #483698;
  font-family: 'Comfortaa', cursive;
  border-color: #483698;
}

.btn-primary:hover {
  background-color: white;
  color: #483698;
  border-color: #483698;
}

.btn-primary:focus {
  
  background-color: white;
  color: #483698;
  border-color: #483698;
}

#progress-label {
  font-family: 'Comfortaa', cursive;
  color: #483698;
}

.progress-bar {
  background-color: #483698;
}

.container {
  background-color: #ffffff;
}

.form-control, .form-select {
  border-color: #483698;
}

.back-button {
  background-color: transparent;
  border-color: transparent;
}
</style>
