<script>
	const references = [
		'<p>Bruni-Bossio, V., & Willness, C. (2016). The “Kobayashi Maru” Meeting: High-Fidelity</p><p class="indent-5">Experiential Learning. Journal of Management Education, 40(5), 619–647.</p><p class="indent-5 text-blue-700 hover:underline"><a href="https://doi.org/10.1177/1052562916644284">https://doi.org/10.1177/1052562916644284</a></p>',
		'<p>Meyer, N. (Director). (1982). Star Trek II: The Wrath of Khan [Film]. Paramount Pictures.</p>',
		'<p>Marrone, T. (n.d.). Class III Neutronic Fuel Carrier (The Kobayashi Maru). ArtStation.com.</p><p class="indent-5 text-blue-700 hover:underline"><a class="indent-5 text-blue-700 hover:underline" href="https://thomasmarrone.artstation.com/projects/34yJJ">https://thomasmarrone.artstation.com/projects/34yJJ</a></p>',
		'<p>OpenAI. (2023). DALL·E 3 [Software]. OpenAI. <a class="text-blue-700 hover:underline" href="https://www.openai.com/dall-e-3/">https://https://www.openai.com/dall-e-3/</a></p>',
		'<p>Stemwedel, J. (2015, August 23). The Philosophy of Star Trek: The Kobayashi Maru, No-Win Scenarios, And Ethical Leadership. Forbes.</p><p class="indent-5"><a class="text-blue-700 hover:underline" href="https://www.forbes.com/sites/janetstemwedel/2015/08/23/the-philosophy-of-star-trek-the-kobayashi-maru-no-win-scenarios-and-ethical-leadership/">https://www.forbes.com/sites/janetstemwedel/2015/08/23/the-philosophy-of-star-trek-the-kobayashi-maru-no-win-scenarios-and-ethical-leadership/</a></p>',
		'<p>Conti, G., & Caroland, J. (2011). Embracing the Kobayashi Maru:</p><p class="indent-5">Why You Should Teach Your Students to Cheat. IEEE Security & Privacy, 9(4), </p><p class="indent-5">48-51. <a class="text-blue-700 hover:underline" href="https://doi.org/10.1109/MSP.2011.80">https://doi.org/10.1109/MSP.2011.80</a></p>'
	];
</script>

<h1 class="text-4xl font-bold text-center bg-black bg-opacity-50 text-gray-100 p-6">
	References (APA formatted)
</h1>

{#each references as reference}
	<div class="rounded p-6 bg-gray-200 w-4/5 mx-auto border border-black space-y-4">
		{@html reference}
	</div>
	<br />
{/each}

<div class="rounded p-1 mx-auto border bg-blue-100">
	<p class="text-center font-mono">
		Go back to <a href="/" class="text-blue-800 hover:underline">Article</a>
	</p>
</div>
