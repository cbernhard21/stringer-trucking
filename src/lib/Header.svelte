<script>
	import Nav from '$lib/components/Nav.svelte';

	export let phoneNumber;
</script>

<header class="bg-black flex flex-row flex-between">
	<div class="logo-container">
		<img src="/images/logo-company-name-bee.png" alt="Logo" />
	</div>

	<div class="truck-logo-container">
		<img src="/images/logo-truck-header.png" alt="Truck Logo" />
		<p>{phoneNumber}</p>
	</div>

	<Nav />
</header>

<style>
	header {
		width: 95%;
		margin: 0 auto;
	}
</style>
