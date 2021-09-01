<script>
  import R from "./R.svelte";
</script>

<header id="header-container">
  <div id="header" class="sticky-header">
    <div class="branding">
      <R />
      <h2 class="roraweb">Roraweb</h2>
    </div>
    <nav class="nav-menu">
      <li>
        <a href="">Home</a>
      </li>
      <li>
        <a href="">Services</a>
      </li>
      <li>
        <a href="">Portfolio</a>
      </li>

      <li>
        <a href="">Contact</a>
      </li>
    </nav>

    <div>
      <div class="contact-button">
        <a href=""> Contact Us</a>
      </div>
    </div>
  </div>
</header>

<style>
  .header {
    position: absolute;
    top: 0;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: white;
    margin: 1rem;
    max-width: 1200px;
    margin-right: auto;
    margin-left: auto;
  }

  a,
  ul,
  li {
    text-decoration: none;
    list-style-type: none;
    color: white;
    font-size: 18px;
    font-weight: 700;
    display: inline-block;
    position: relative;
  }

  .branding {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .roraweb {
    margin-left: 10px;
  }
  .nav-menu {
    justify-content: space-evenly;
    align-items: center;
    display: flex;
    width: 50%;
  }
  header {
    position: static;
  }

  @keyframes slideup {
    0% {
      top: -50px;
    }
    100% {
      top: 0;
    }
  }
  .contact-button {
    border: 3px solid white;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
  }
  .contact-button:hover {
    background-color: white;
    transition: 0.25s;
  }
  .contact-button:hover a {
    color: black;
  }
</style>
