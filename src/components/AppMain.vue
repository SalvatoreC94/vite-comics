<template>
    <main class="main-content">
      <section class="content-placeholder">
        <!-- inserire contenuti principali -->
        <h1>--&gt Content goes here &lt--</h1>
      </section>
      <section class="container-merch">
      <!-- inserire immanigi -->
        <h1>--&gt Qui vanno aggiunti i loghi &lt--</h1>
      </section>
      
    </main>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style scoped>
  .main-content {
    position: relative;
    background-color: #1c1c1c; 
    text-align: center;
    min-height: 150px;
   
  }
  
  .content-placeholder {
    color:white;
    z-index: 1; 
    font-size: 2rem;
    position: relative;
  }
  
  .main-content::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    /* background-image: url('../assets/img/'); */
    background-size: cover;
    background-repeat: no-repeat;
     }

     .container-merch {
    
    background-color:#0282F9;
   ;
    text-align: center;
    min-height: 100px;
  }
  </style>
  
  