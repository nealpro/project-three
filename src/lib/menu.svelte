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
		<div class="lg:flex justify-center w-full py-3">
			{#each items as item, index}
				{#if index === 0}
					<a
						href={item.href}
						class="font-semibold px-6 py-2 leading-6 bg-white text-gray-900 text-xl"
						id="left-rounder"
					>
						{item.name}
					</a>
				{:else if index === items.length - 1}
					<a
						href={item.href}
						class="font-semibold px-6 py-2 leading-6 bg-white text-gray-900 text-xl"
						id="right-rounder"
					>
						{item.name}
					</a>
				{:else}
					<a
						href={item.href}
						class="font-semibold px-6 py-2 leading-6 bg-white text-gray-900 text-xl"
						id="item"
					>
						{item.name}
					</a>
				{/if}
			{/each}
		</div>
	</nav>
</header>

<style lang="postcss">
	:global(html) {
		background-image: url('/abstract.png');
	}
	#left-rounder {
		border-top-left-radius: 20px;
		border-bottom-left-radius: 20px;
		border-color: black;
		border-width: 1px;
	}
	#right-rounder {
		border-top-right-radius: 20px;
		border-bottom-right-radius: 20px;
		border-color: black;
		border-width: 1px;
	}
	#item {
		border-color: black;
		border-width: 1px;
	}
</style>
