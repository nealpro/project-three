<script>
	const references = [
		'<p>Meyer, N. (Director). (1982). <i>Star Trek II: The Wrath of Khan</i> [Film]. Paramount Pictures.</p>',
		'<p>Marrone, T. (n.d.). <i>Class III Neutronic Fuel Carrier (The Kobayashi Maru)</i>. ArtStation.com.</p><p class="indent-5 text-blue-700 hover:underline"><a class="indent-5 text-blue-700 hover:underline" href="https://thomasmarrone.artstation.com/projects/34yJJ">https://thomasmarrone.artstation.com/projects/34yJJ</a></p>',
		'<p>OpenAI. (2023). <i>DALL·E 3</i> [Software]. OpenAI. <a class="text-blue-700 hover:underline" href="https://www.openai.com/dall-e-3/">https://https://www.openai.com/dall-e-3/</a></p>',
		'<p>Bruni-Bossio, V., & Willness, C. (2016). The "Kobayashi Maru" Meeting: High-Fidelity</p><p class="indent-5">Experiential Learning. <i>Journal of Management Education</i>, 40(5), 619–647.</p><p class="indent-5 text-blue-700 hover:underline"><a href="https://doi.org/10.1177/1052562916644284">https://doi.org/10.1177/1052562916644284</a></p>',
		'<p>Conti, G., & Caroland, J. (2011). <i>Embracing the Kobayashi Maru:</p><p class="indent-5">Why You Should Teach Your Students to Cheat.</i> IEEE Security & Privacy, 9(4), </p><p class="indent-5">48-51. <a class="text-blue-700 hover:underline" href="https://doi.org/10.1109/MSP.2011.80">https://doi.org/10.1109/MSP.2011.80</a></p>',
		'<p>Stemwedel, J. (2015, August 23). <i>The Philosophy of Star Trek: The Kobayashi Maru, No-Win Scenarios, And Ethical Leadership.</i> Forbes.</p><p class="indent-5"><a class="text-blue-700 hover:underline" href="https://www.forbes.com/sites/janetstemwedel/2015/08/23/the-philosophy-of-star-trek-the-kobayashi-maru-no-win-scenarios-and-ethical-leadership/">https://www.forbes.com/sites/janetstemwedel/2015/08/23/the-philosophy-of-star-trek-the-kobayashi-maru-no-win-scenarios-and-ethical-leadership/</a></p>',
		'<p>Eisenberg, A. (2018, February 20). <i>The Educator\'s Guide to the "Kobayashi Maru"</i>. The Times of Israel. </p><p class="indent-5"><a href="https://blogs.timesofisrael.com/the-educators-guide-to-the-kobayashi-maru/" class="text-blue-700 hover:underline">https://blogs.timesofisrael.com/the-educators-guide-to-the-kobayashi-maru/</a></p>'
	];
</script>

<h1 class="text-4xl font-bold text-center bg-black bg-opacity-50 text-white p-6 font-sans">
	References (APA formatted)
</h1>

{#each references as reference}
	<div class="rounded p-6 bg-white w-4/5 mx-auto border border-black space-y-4 font-sans">
		{@html reference}
	</div>
	<br />
{/each}

<div class="rounded p-1 mx-auto border bg-blue-100">
	<p class="text-center font-mono">
		Go back to <a href="/" class="text-blue-800 hover:underline">Article</a>
	</p>
</div>

<div class="h-screen"></div>
