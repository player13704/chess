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
	<p>© Copyright Felix</p>
</footer>

<style>
	header {
		display: flex;
		justify-content: center;
		background-color: rgba(0, 0, 0, 0.1);
	}
	main {
		justify-content: center;
		margin: 20px;
	}
	footer {
		text-align: center;
	}
</style>
