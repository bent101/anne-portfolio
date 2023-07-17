<script>
	import Bubble from "$lib/components/Bubble.svelte";
	import anne from "$lib/images/anne.jpeg";
	import youtube from "$lib/images/youtube.png";
	import email from "$lib/images/email.png";
</script>

<div class="mx-auto max-w-5xl px-8 py-16">
	<div class="flex gap-2">
		<h1 class="text-5xl sm:text-6xl font-serif font-bold mr-4">Anne Dyke</h1>
		<Bubble href="https://www.youtube.com/@AnneDykeFlute/videos" icon={youtube} />
		<Bubble href="mailto:annedyke@gmail.com" icon={email} />
	</div>
	<h2 class="text-2xl font-bold pb-8">Professional Flutist</h2>

	<img
		src={anne}
		alt="Anne Dyke's headshot"
		class="sm:float-right mb-8 float-none w-80 mx-auto md:w-96 sm:ml-8 rounded-2xl"
	/>

	<p class="pb-4 text-lg">
		A native of North Carolina, Anne is a professional flutist who performs and teaches in the
		Raleigh area. Her resume includes teaching lessons to beginning, intermediate and advanced
		students. She enjoys teaching and helping her students build confidence in their ability. She
		maintains a large flute studio and her students consistently place into All-State, All-District
		and All-County bands, as well as the local Triangle Youth Philharmonic, Symphony and Orchestra
		programs. She also teaches beginning to intermediate piano students at KinderVillage in Cary, NC
		as well as her home studio.
	</p>

	<p class="pb-4 text-lg">
		Anne holds degrees from Florida State University (Doctorate of Music), University of Illinois
		(Master of Music), and the University of North Carolina at Chapel Hill (Bachelor of Music
		Education), where she studied with Charles DeLaney, Alex Murray and Brooks de Wetter Smith.
		After her Master's degree, she moved to Chicago to study with Walfrid Kujala, former piccoloist
		of the Chicago Symphony Orchestra, where she studied orchestral and solo repertoire in depth.
	</p>

	<p class="pb-4 text-lg">
		In addition to teaching at her home studio, Anne was also Adjunct Flute Instructor at UNC-CH
		from 2000-2005 teaching music majors, minors and non-majors. She also served as Interim Flute
		Instructor teaching and performing with the faculty woodwind quintet in 2005 for Brooks de
		Wetter Smith during his sabbatical. She held Adjunct positions at Shaw University (teaching
		flute) and Wake Technical Community College (teaching music appreciation classes). She has also
		taught band, strings and general music in public and private schools in North Carolina, Illinois
		and Texas.
	</p>

	<p class="pb-4 text-lg">
		For three years, Anne was a substitute in the North Carolina Symphony. She attended the Aspen
		Music Festival and won the National Flute Association Orchestral Masterclass with Bernard
		Goldberg in 1989 in New Orleans. She currently serves on the Board of Directors of the Raleigh
		Area Flute Association and founded of the yearly Solofest Contest which is very popular and has
		over 125 flutists participate.
	</p>

	<p class="pb-4 text-lg">
		Subscribe and check out her Youtube channel, <a
			class="font-semibold hover:underline hover:underline-offset-2"
			href="https://www.youtube.com/@AnneDykeFlute/videos"
			target="_blank">Anne Dyke Flute</a
		> and play a duet with her!
	</p>
</div>
