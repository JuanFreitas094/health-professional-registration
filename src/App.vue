<template>
  <AttendanceAbout/>
</template>

<script>
import AttendanceAbout from './components/attendance-about.vue'

export default {
  name: 'App',
  components: {
    AttendanceAbout,
}
}
</script>

<style>
#App {
  font-family: 'Open Sans', sans-serif; 
}

body{
  background-color: #ffe766;
}

.main-title {
  font-family:  'Comfortaa', cursive;
  color: #483696;
}

.btn-primary {
  background-color: #483696;
  font-family: 'Comfortaa', cursive;
  border-color: #483696;
}

.btn-primary:hover {
  background-color: white;
  color: #483696;
  border-color: #483696;
}

.btn-primary:focus {
  
  background-color: white;
  color: #483696;
  border-color: #483696;
}

#progress-label {
  font-family: 'Comfortaa', cursive;
  color: #483696;
}

.progress-bar {
  background-color: #483696;
}

.container {
  background-color: #ffffff;
}

.form-control, .form-select {
  border-color: #483696;
}

</style>
