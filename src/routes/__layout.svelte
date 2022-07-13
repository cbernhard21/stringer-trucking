<script>
	import '$lib/css/global.css';

	import Header from '$lib/Header.svelte';
	import Footer from '$lib/Footer.svelte';

	let phoneNumber = '555-555-5555';
</script>

<div class="header-container bg-black">
	<Header {phoneNumber} />
</div>

<slot />

<div class="footer-container">
	<Footer />
</div>

<style>
</style>
