<script>
	import '../app.css';
	import Menu from '$lib/menu.svelte';
	const menuItems = [
		{ name: 'Article', href: '/' },
		{ name: 'References', href: '/references' },
		{ name: 'About', href: '/about'}
	];
</script>

<Menu items={menuItems} />

<slot />
