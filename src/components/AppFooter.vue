<template>
    <footer>
      <!-- Parte superiore del footer -->
      <div class="footer-top">
        <div class="container">
          <div class="footer-links">
            <div class="link-column">
              <h4>DC COMICS</h4>
              <ul>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
              </ul>
            </div>
            <div class="link-column">
              <h4>DC</h4>
              <ul>
                <li><a href="#">Terms Of Use</a></li>
                <li><a href="#">Privacy policy</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscriptions</a></li>
                <li><a href="#">Talent Worksshop</a></li>
                <li><a href="#">CPCS Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>
               
              </ul>
            </div>
            <div class="link-column">
              <h4>SITES</h4>
              <ul>
                <li><a href="#">DC</a></li>
                <li><a href="#">MAD Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Universe</a></li>
                <li><a href="#">DC Power Visa</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Parte inferiore del footer -->
      <div class="footer-bottom">
        <div class="container">
          <button class="signup-button">SIGN-UP NOW!</button>
          <div class="social-media">
            <h4>FOLLOW US</h4>
            <ul>
              <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="Facebook"></a></li>
              <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="Twitter"></a></li>
              <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="YouTube"></a></li>
              <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="Pinterest"></a></li>
              <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="Location"></a></li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style scoped>
  /* Parte superiore del footer */
  .footer-top {
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    background-position: center;
    padding: 40px 0;
    color: white;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    display: flex;
    justify-content: space-between;
  }
  
  .footer-links {
    display: flex;
    justify-content:flex-start;
    width: 100%;
  }
  
  .link-column h4 {
    font-size: 1.2rem;
    margin-bottom: 10px;
    margin: 10px;
  }
  
  .link-column ul {
    list-style-type: none;
    padding: 0;
  }
  
  .link-column ul li {
    margin-bottom: 8px;
    font-size: x-small;
  }
  
  .link-column ul li a {
    color:gray;
    text-decoration: none;
  }
  
  .link-column ul li a:hover {
    text-decoration: underline;
  }
  
  /* Parte inferiore del footer */
  .footer-bottom {
    background-color: #1c1c1c; /* Sfondo scuro come nell'immagine di esempio */
    padding: 20px 0;
    color: white;
    text-align: center;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .signup-button {
    background-color: #0278ff;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    font-size: 1rem;
    text-transform: uppercase;
  }
  
  .signup-button:hover {
    background-color: #025bb5;
  }
  
  .social-media {
    display: flex;
    align-items: center;
  }
  
  .social-media h4 {
    margin-right: 10px;
    font-size: 1rem;
    color: #0278ff;
  }
  
  .social-media ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    gap: 15px;
  }
  
  .social-media ul li {
    margin: 0;
  }
  
  .social-media ul li img {
    width: 25px;
  }
  
  .social-media ul li a {
    color: white;

  }
  </style>
  