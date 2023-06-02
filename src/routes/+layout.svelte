<script lang="ts">
	import '../app.postcss';
	import './style.css';
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
</script>

<div>
	<Header />

	<div class="page-layout">
		<main>
			<slot />
		</main>
	</div>

	<Footer />
</div>

<style lang="postcss">

	.page-layout {
		max-width: 1600px;
		margin: 0 auto;
	}
</style>
