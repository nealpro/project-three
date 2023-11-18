<script>
	const references = [
		'<p>Bruni-Bossio, V., & Willness, C. (2016). The “Kobayashi Maru” Meeting: High-Fidelity</p><p class="indent-5">Experiential Learning. Journal of Management Education, 40(5), 619–647.<br></p><p class="indent-5 text-blue-700 hover:underline"><a href="https://doi.org/10.1177/1052562916644284">https://doi.org/10.1177/1052562916644284</a></p>',
		'<p>Meyer, N. (Director). (1982). Star Trek II: The Wrath of Khan [Film]. Paramount Pictures.</p>'
	];
</script>

<h1 class="text-4xl font-bold text-center p-6">References</h1>

{#each references as reference}
	<div class="rounded p-6 bg-white w-4/5 mx-auto border border-black space-y-4">
		{@html reference}
	</div>
	<br />
{/each}
<div class="rounded p-1 mx-auto border bg-blue-100">
	<p class="text-center font-mono">
		Go back to <a href="/" class="text-blue-800 hover:underline">Article</a>
	</p>
</div>
