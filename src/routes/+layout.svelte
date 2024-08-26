<script>
  import "../app.css";
</script>
<div class="min-h-screen text-white bg-police-blue">
  <header class="flex items-center">
    <img src="/assets/logo.svg" alt="myteam logo">
    <nav>
      <a href="/">Home</a>
      <a href="/about">About</a>
      <a href="/contact">Contact</a>
    </nav>
  </header>
  <slot />
  <footer class='absolute bottom-0 flex w-full bg-dark-green'>
    <div>
      <img src="/assets/logo.svg" alt="myteam logo">
      <nav>
        <a href="/">Home</a>
        <a href="/about">About</a>
      </nav>
    </div>
  </footer>
</div>