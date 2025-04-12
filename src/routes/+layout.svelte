<script lang="ts">
	import '../app.css';
	import Footer from '../components/sections/Footer.svelte';
	import Header from '../components/sections/Header.svelte';
	
	let { children } = $props();
</script>

<div class="app">
	<Header />
	<main>
		{@render children()}
	</main>
  <Footer/>
</div>

<style></style>
