<script>
  import Header from "$lib/header/Header.svelte";
  import "../app.postcss";
</script>

<Header />

<main>
  <slot />
</main>

<footer class="bg-color p-7">
  
<h1 class="text-center text-lg">Built with 🐹 by Team Hashira during MetaBuild</h1>

</footer>

<style>

.bg-color {
	background-color: #FFAAA6;
  }
 
</style>
