<script>
	import { onMount } from 'svelte';

	onMount(() => {
		if (window.innerWidth < 768) {
			alert('This website is not meant for mobile. Would you like to proceed?');
		}
	});

	const content1 = [
		"The Kobayashi Maru is a fictional exercise in the <i>Star Trek</i> universe, first introduced in the film <i>Star Trek II: The Wrath of Khan</i> (1982) and gained its popularity from that movie; however, it has appeared several times in the <i>Star Trek</i> franchise since then. It is a training exercise for cadets at the <i>Starfleet Academy</i>, designed to be a no-win scenario. The purpose of the test is to evaluate a cadet's character and command capabilities when faced with an impossible situation. In the scenario, a cadet is placed in command of a starship and receives a distress signal from the Kobayashi Maru, a civilian vessel stranded in the <i>Klingon Neutral Zone</i>. Any attempt to rescue the ship violates the <i>Neutral Zone</i> treaty and invites Klingon hostility, but ignoring the distress call contradicts Starfleet's humanitarian mission. The situation is engineered to be unwinnable, ensuring the cadet's failure.",
		'The Kobayashi Maru gained significant popularity and cultural significance because of its association with the character James T. Kirk. Kirk is famously known for being the only person to have ever "beaten" the test by surreptitiously reprogramming the simulation so that a rescue was possible, thus demonstrating his aversion to accepting defeat. This act showcased his character\'s ingenuity, resourcefulness, and refusal to accept no-win scenarios, traits that became central to his identity in the <i>Star Trek</i> franchise.',
		'<img src="starship.jpg" class="mx-auto" /><br><p class="text-center">Class III Neutronic Fuel Carrier (The Kobayashi Maru) by Thomas Marrone (n.d.).</p>'
	];

	const content2_1 = [
		'Over the years, the term <i>Kobayashi Maru</i> has entered broader pop culture. It is often used metaphorically to describe any situation where all available options are undesirable or where success seems unattainable. This reflects its role in <i>Star Trek</i> as a symbol of character test under pressure and moral dilemma, resonating with audiences beyond the science fiction genre. Today, the Kobayashi Maru continues to be a significant reference in discussions about ethics, leadership, and problem-solving, both within and outside the realm of <i>Star Trek</i> fandom. It is frequently cited in various media, literature, and even in professional and academic contexts as an archetype of an unwinnable scenario and a test of character and decision-making.'
	];

	const content2_2 = [
		'"The Kobayashi Maru scenario has become a valuable tool for experiential learning, especially in the context of nonprofit governance. An article by Bruni-Bossio and Willness (2016) says, "The Kobayashi Maru Meeting is a simulation with high physical and psychological fidelity—that is, one that closely resembles the \'look and feel\' of real-world board governance." The authors\' innovative approach outlines the versatility of the Kobayashi Maru scenario as an educational tool. Bruni-Bossio and Willness successfully adapted the Kobayashi Maru scenario to create a board meeting simulation that mimics the high stakes and complex dynamics of real-world governance. The simulation incorporates principles from acting literature, theories, and research in training and development to encourage participants to engage with sensitive topics that challenge the values of the trainees.',
		'As indicated in an article by Bruni-Bossio & Willness, (2016) “results from multisource, multimethod data suggest that the simulation enhanced students\' decision making, critical thinking, and communication skills, as well as their ability to deal with their own and others\' reactions in intense circumstances.” It is evident that the Kobayashi Maru scenario is a good educational tool. There have been other instances where the Kobayashi Maru situation was utilized in educational settings to foster unique and valuable learning experiences. For instance, in the paper by Conti and Caroland (2011), the authors argue for the teaching of unconventional problem-solving methods, including the idea of teaching students to "cheat" in a controlled and ethical manner. This approach, inspired by the Kobayashi Maru scenario, emphasizes the importance of thinking outside traditional frameworks and norms, particularly in fields like cybersecurity and information technology, where innovative and unorthodox thinking can be crucial.'
	];
</script>

<h1 class="text-4xl font-bold text-center bg-black bg-opacity-50 text-gray-100 p-6">
	Project Three: Kobayashi Maru Across Media and Academia
</h1>

<div class="w-4/5 mx-auto bg-gray-500 rounded-3xl border-black border-8 px-6">
	<h2 class="text-3xl font-semibold text-white text-center py-4">What is Kobayashi Maru?</h2>

	{#each content1 as item}
		<div class="rounded p-6 bg-gray-200 w-full mx-auto border border-black">
			<p>
				{@html item}
			</p>
		</div>
		<br />
	{/each}
</div>

<br />

<div class="w-4/5 mx-auto bg-gray-500 rounded-3xl border-black border-8 px-6">
	<h2 class="text-3xl font-semibold text-white text-center py-4">Kobayashi Maru in pop culture</h2>
	{#each content2_1 as item}
		<div class="rounded p-6 bg-gray-200 w-full mx-auto border border-black">
			<p>
				{@html item}
			</p>
		</div>
		<br />
	{/each}

	<h2 class="text-2xl text-white text-center py-3">Kobayashi Maru in pop culture</h2>

	{#each content2_2 as item}
		<div class="rounded p-6 bg-gray-200 w-full mx-auto border border-black">
			<p>
				{@html item}
			</p>
		</div>
		<br />
	{/each}
</div>

<div class="h-screen"></div>

{#each content2_2 as item}
	<div class="rounded p-6 bg-gray-200 w-4/5 mx-auto border border-black">
		<p>
			{@html item}
		</p>
	</div>
	<br />
{/each}

<div class="h-screen"></div>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}

	:global(body) {
		font-family: 'Exo', sans-serif;
	}
</style>
