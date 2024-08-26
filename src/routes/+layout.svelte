<script>
  import "../app.css";
</script>
<div class="min-h-screen text-white bg-police-blue">
  <header class="flex items-center">
    <img src="/assets/logo.svg" alt="">
    <nav>
      <a href="/">Home</a>
      <a href="/about">About</a>
      <a href="/contact">Contact</a>
    </nav>
  </header>
  <slot />
</div>