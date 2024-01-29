<script>
	import Layout from '../lib/layout.svelte';
	import '../styles/global.css';
</script>

<header>
	<Layout title="Chess" />
</header>

<main>
	<slot />
</main>

<footer>
	<p>my chess website</p>
</footer>

<style>
	header {
		display: flex;
		justify-content: center;
	}
	main {
		justify-content: center;
		margin: 20px;
	}
	footer {
		text-align: center;
	}
</style>
