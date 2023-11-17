<script>
	const content = [
		"The Kobayashi Maru is a fictional exercise in the <i>Star Trek</i> universe, first introduced in the film <i>Star Trek II: The Wrath of Khan</i> (1982) and gained its popularity from that movie; however, it has appeared several times in the <i>Star Trek</i> franchise since then. It's a training exercise for cadets at the <i> Starfleet Academy</i>, designed to be a no-win scenario. The purpose of the test is to evaluate a cadet's character and command capabilities when faced with an impossible situation.",
		"In the scenario, a cadet is placed in command of a starship and receives a distress signal from the Kobayashi Maru, a civilian vessel stranded in the “Klingon Neutral Zone”. Any attempt to rescue the ship violates the “Neutral Zone” treaty and invites Klingon hostility, but ignoring the distress call contradicts Starfleet's humanitarian mission. The situation is engineered to be unwinnable, ensuring the cadet's failure.",
	];
</script>

<h1 class="text-4xl font-bold text-center p-6">Project Three: Kobayashi Maru</h1>

<h2 class="text-4xl font-semibold text-center p-4">What is Kobayashi Maru?</h2>

{#each content as item}
	<div class="rounded p-6 bg-white w-4/5 mx-auto border border-black">
		<p>
			{@html item}
		</p>
	</div>
	<br />
{/each}

<slot />

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}
</style>
