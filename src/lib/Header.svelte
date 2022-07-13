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

	<div class="nav-container">
		<Nav />
	</div>
</header>

<style>
	header {
		width: 95%;
		margin: 0 auto;
		padding: 2rem 0;
	}

	.logo-container {
		max-width: 15rem;
		align-self: center;
	}

	.truck-logo-container {
		align-self: center;
	}

	.nav-container {
		align-self: center;
	}
</style>
