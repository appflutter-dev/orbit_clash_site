<script>
  export let title = "Orbit Clash";
</script>

<header class="app-header">
  <img src="icon_app.png" alt="Orbit Clash Logo" class="app-logo" />
  <h1 class="app-title">{title}</h1>
</header>

<style>
  .app-header {
    display: flex;
    align-items: center;
    background-color: #4caf50;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }

  .app-logo {
    height: 50px;
    margin-right: 1rem;
  }

  .app-title {
    color: white;
    font-size: 1.5rem;
    font-weight: bold;
  }
</style>
