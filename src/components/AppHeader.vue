<template>
    <header>
      <nav>
        <img src="..\assets\img\dc-logo.png" alt="DC Logo" class="logo">
        <ul>
          <li v-for="item in menuItems" :key="item">{{ item }}</li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    data() {
      return {
        menuItems: ['Characters', 'Comics', 'Movies', 'TV', 'Games', 'Collectibles', 'Videos', 'Fans', 'News', 'Shop']
      };
    }
  };
  </script>
  
  <style scoped>
  .logo {
    width: 70px;
  }
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
  }
  ul {
    list-style: none;
    display: flex;
    gap: 20px;
  }
  li {
    cursor: pointer;
  }
  </style>