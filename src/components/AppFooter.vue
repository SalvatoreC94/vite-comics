<template>
  <footer>
    <div class="footer-section">
      <h3>DC Comics</h3>
      <ul>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>
      </ul>
    </div>
    <div class="footer-section">
      <h3>DC</h3>
      <ul>
        <li>Terms Of Use</li>
        <li>Privacy Policy</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
      </ul>
    </div>
    <div class="footer-section">
      <h3>Sites</h3>
      <ul>
        <li>DC</li>
        <li>Mad Magazine</li>
        <li>DC Kids</li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  background-color: #333;
  color: white;
  display: flex;
  justify-content: space-around;
  padding: 20px;
}
.footer-section {
  display: flex;
  flex-direction: column;
}
.footer-section ul {
  list-style: none;
  padding: 0;
}
</style>
