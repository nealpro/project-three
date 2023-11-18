<script>
	const content1 = [
		"The Kobayashi Maru is a fictional exercise in the <i>Star Trek</i> universe, first introduced in the film <i>Star Trek II: The Wrath of Khan</i> (1982) and gained its popularity from that movie; however, it has appeared several times in the <i>Star Trek</i> franchise since then. It's a training exercise for cadets at the <i>Starfleet Academy</i>, designed to be a no-win scenario. The purpose of the test is to evaluate a cadet's character and command capabilities when faced with an impossible situation.",
		"In the scenario, a cadet is placed in command of a starship and receives a distress signal from the Kobayashi Maru, a civilian vessel stranded in the “Klingon Neutral Zone”. Any attempt to rescue the ship violates the “Neutral Zone” treaty and invites Klingon hostility, but ignoring the distress call contradicts Starfleet's humanitarian mission. The situation is engineered to be unwinnable, ensuring the cadet's failure.",
		'The Kobayashi Maru gained significant popularity and cultural significance because of its association with the character James T. Kirk. Kirk is famously known for being the only person to have ever "beaten" the test by surreptitiously reprogramming the simulation so that a rescue was possible, thus demonstrating his aversion to accepting defeat. This act showcased his character\'s ingenuity, resourcefulness, and refusal to accept no-win scenarios, traits that became central to his identity in the <i>Star Trek</i> franchise.'
	];

	const content2 = [
		"Over the years, the term <i>Kobayashi Maru</i> has entered broader pop culture. It's often used metaphorically to describe any situation where all available options are undesirable or where success seems unattainable. This reflects its role in <i>Star Trek</i> as a symbol of character test under pressure and moral dilemma, resonating with audiences beyond the science fiction genre."
	];
</script>

<h1 class="text-4xl font-bold text-center p-6">Project Three: Kobayashi Maru</h1>

<h2 class="text-4xl font-semibold text-center p-4">What is Kobayashi Maru?</h2>

{#each content1 as item}
	<div class="rounded p-6 bg-white w-4/5 mx-auto border border-black">
		<p>
			{@html item}
		</p>
	</div>
	<br />
{/each}

<h2 class="text-4xl font-semibold text-center p-4">Kobayashi Maru in pop culture</h2>

{#each content2 as item}
	<div class="rounded p-6 bg-white w-4/5 mx-auto border border-black">
		<p>
			{@html item}
		</p>
	</div>
	<br />
{/each}

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}
</style>
