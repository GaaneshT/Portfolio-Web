<!-- src/routes/+layout.svelte -->
<script>
	import Navbar from '$lib/Navbar.svelte';
    import '../global.css';
</script>

<Navbar />

<main>
	<slot />
</main>

<!-- Optionally add a footer, too -->
<footer class="text-center p-4 text-sm text-gray-500 dark:text-gray-400">
  © 2024 Gaanesh.
</footer>
