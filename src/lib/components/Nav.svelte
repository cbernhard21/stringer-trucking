<script>
	let routes = [
		{
			link: '/',
			label: 'Home'
		},
		{
			link: 'about',
			label: 'About'
		},
		{
			link: 'services',
			label: 'Services'
		},
		{
			link: 'contact',
			label: 'Contact'
		}
	];
</script>

<nav>
	<ul class="flex flex-row">
		{#each routes as route}
			<li><a href={route.link} class="text-white">{route.label}</a></li>
		{/each}
	</ul>
</nav>

<style>
	a {
		text-decoration: none;
	}

	ul {
		list-style-type: none;
	}
</style>
