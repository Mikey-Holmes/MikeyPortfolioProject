<script>
</script>

<nav>
  <ul>
    <li><a href="/">Home</a></li>
    <li><a href="/art">My Artwork</a></li>
    <li><a href="/games">Games I've Created</a></li>
    <li><a href="/CV">My CV</a></li>
    <li><a href="/AboutMe">About Me</a></li>
  </ul>
</nav>

<style>
  nav {
    width: 100%;
    background-color: #111; 
    position: sticky;
    top: 0;
    z-index: 1000;
    background-color: #607D8B;

  }

  nav ul {
    margin: 0;
    padding: 0;
    list-style: none;
    display: flex;
    justify-content: center; 
    align-items: center;
    height: 60px; 
  }

  nav ul li {
    margin: 0 40px; 
  }

  nav ul li a {
    color: white;
    text-decoration: none;
    font-family: 'Poppins', sans-serif;
    font-weight: bold;
    font-size: 1rem;
    transition: color 0.3s ease;
  }

  nav ul li a:hover {
    color: #5dade2;
  }

  @media (max-width: 768px) {
    nav ul {
      flex-direction: column;
      height: auto;
      padding: 10px 0;
    }

    nav ul li {
      margin: 10px 0;
    }
  }
</style>