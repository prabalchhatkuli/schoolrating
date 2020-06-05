<template>
  <div class="home">
    <h1>Welcome to Nepal School Ratings.</h1>
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
