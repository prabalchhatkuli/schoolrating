<template>
  <div class="home">
    <h1>Welcome to Nepal School Ratings.</h1>
    <h4>Search for better education</h4>
    <p>project developed using Vue.js</p>
    <img alt="Vue logo" src="../assets/logo.png">
    <HomePageContent/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomePageContent from '@/components/Home.component.vue'

export default {
  name: 'Home',
  components: {
    HomePageContent
  }
}
</script>
