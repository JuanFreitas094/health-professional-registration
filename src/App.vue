<template>
  <RegistrationReview/>
  <AttendanceAbout/>
  <ProfessionalData/>
</template>

<script>
import RegistrationReview from './components/registration-review.vue'
import AttendanceAbout from './components/attendance-about.vue'
import ProfessionalData from './components/professional-data.vue'

export default {
  name: 'App',
  components: {
    RegistrationReview,
    AttendanceAbout,
    ProfessionalData
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

</style>
