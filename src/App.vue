<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="heading">
      <h1>ಮೈತ್ರೀ ಪ್ರತಿಷ್ಠಾನ</h1>
    </div>

    <div class="topnav">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
      <RouterLink to="/about" style="float:right">About</RouterLink>
    </div>

  </header>

  <body>
    <RouterView />

  </body>
</template>

<style scoped>


/* Header/Blog Title */
.heading {
  padding: 30px;
  text-align: center;
  background: white;
}

.heading h1 {
  font-size: 50px;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}


</style>
