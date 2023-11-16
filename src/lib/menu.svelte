<!-- Menu.svelte -->
<script>
	// Prop for menu items
	/**
	 * @type {Array<{name: string, href: string}>}
	 */
	export let items = [];
</script>

<header>
	<nav class="mx-auto" aria-label="Global">
		<div class="lg:flex justify-center bg-gray-500 w-full py-2">
			{#each items as item, index}
				{#if index === 0}
					<a
						href={item.href}
						class="text-sm font-semibold px-3 leading-6 bg-white text-gray-900"
						id="left-rounder"
					>
						{item.name}
					</a>
				{:else if index === items.length - 1}
					<a
						href={item.href}
						class="text-sm font-semibold px-3 leading-6 bg-white text-gray-900"
						id="right-rounder"
					>
						{item.name}
					</a>
				{:else}
					<a href={item.href} class="text-sm font-semibold px-3 leading-6 bg-white text-gray-900">
						{item.name}
					</a>
				{/if}
			{/each}
		</div>
	</nav>
</header>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}
	#left-rounder {
		border-top-left-radius: 20px;
		border-bottom-left-radius: 20px;
	}
	#right-rounder {
		border-top-right-radius: 20px;
		border-bottom-right-radius: 20px;
	}
</style>
