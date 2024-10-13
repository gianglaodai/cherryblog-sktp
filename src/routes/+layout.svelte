<script>
  import '../app.css';
</script>

<header>
  <nav class="mb-10 py-8 shadow-[0_0_2em_rgba(0,0,0,0.1)]">
    <ul class="flex justify-center gap-8 text-xl">
      <li class="text-orange-600 underline decoration-orange-600 decoration-2 underline-offset-4">
        <a href="/">HOME</a>
      </li>
      <li class="text-blue-700 underline decoration-blue-700 decoration-2 underline-offset-4">
        <a href="/articles">ARTICLES</a>
      </li>
      <li class="text-pink-600 underline decoration-pink-600 decoration-2 underline-offset-4">
        <a href="/about">ABOUT ME</a>
      </li>
      <li class="text-teal-700 underline decoration-teal-700 decoration-2 underline-offset-4">
        <a href="/contact">CONTACT</a>
      </li>
    </ul>
  </nav>
</header>
<main class="mt-24">
  <slot />
</main>
<footer class="pt-10">
  <div class="mt-10 border-t py-10 md:text-center">© 2024 Cherry's Blog. All rights reserved.</div>
</footer>
