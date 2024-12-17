<script>
  export let title = "Banquetes APP";
</script>

<header class="header">
  <div class="container">
    <h1 class="title">{title}</h1>
    <nav class="nav">
      <ul>
        <li><a href="/">Inicio</a></li>
        <li><a href="/about">Acerca de</a></li>
        <li><a href="/contact">Contacto</a></li>
      </ul>
    </nav>
  </div>
</header>

<style>
  .header {
    background-color: #0077cc;
    color: white;
    padding: 1rem 2rem;
    border-radius: 20px;
  }
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .title {
    margin: 0;
    font-size: 1.5rem;
  }
  .nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 1rem;
  }
  .nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
  }
  .nav a:hover {
    text-decoration: underline;
  }
</style>
