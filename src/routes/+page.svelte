<script>
	import Bubble from "$lib/components/Bubble.svelte";
	import anne from "$lib/images/anne.jpeg";
	import anne2 from "$lib/images/anne2.jpeg";
	import youtube from "$lib/images/youtube.png";
	// import email from "$lib/images/email.jpeg";
	import note from "$lib/images/note.png";
</script>

<div class="mx-auto max-w-6xl py-16">
	<header class="top-0 bg-purple-200/80 px-8 py-2 backdrop-blur-md sm:sticky sm:z-10">
		<h1 class="font-serif text-5xl font-bold">
			Anne Dyke
			<div class="inline-block translate-y-2">
				<Bubble href="https://www.youtube.com/@AnneDykeFlute/videos" icon={youtube} />
				<!-- <Bubble href="mailto:annedyke64@gmail.com" icon={email} /> -->
			</div>
		</h1>

		<h2 class="mb-4 text-xl font-bold">Professional Flutist and Teacher in Raleigh</h2>
	</header>

	<main class="px-8">
		<section class="flex flex-col text-black/90 md:flex-row md:gap-8">
			<div class="flex-1">
				<p class="pb-4">
					I am available to teach flute and piano lessons in the Raleigh area. Private lessons are
					designed to take place weekly and in person, though I am equipped to teach lessons online
					on a case-by-case basis should the need arise. Lessons are typically 30, 45, or 60
					minutes. Beginners work well with 30-minute lessons.
				</p>
				<p class="pb-4">
					I am also available to play weddings and other gigs. Please contact me using the form if
					you are interested!
				</p>
			</div>

			<form
				class="flex flex-1 select-none flex-col gap-2"
				action="https://formsubmit.co/af533803167f4b17e5c165b9c5176740"
				method="post"
			>
				<input
					required
					class="rounded-md bg-white/50 px-4 py-2 text-black placeholder:text-black/60"
					type="name"
					name="name"
					placeholder="Your name"
				/>
				<input
					required
					class="rounded-md bg-white/50 px-4 py-2 text-black placeholder:text-black/60"
					type="email"
					name="email"
					placeholder="Your email"
				/>
				<textarea
					required
					class="rounded-md bg-white/50 px-4 py-2 text-black placeholder:text-black/60"
					name="message"
					rows="7"
					placeholder="Message"
				/>
				<button
					type="submit"
					class="ml-auto block rounded-md bg-black/80 px-8 py-2 text-lg font-semibold text-white"
					>Send</button
				>
			</form>
		</section>

		<section class="text-black/90">
			<h2 class="my-4 text-2xl font-bold">About Anne</h2>

			<div
				class="float-none mb-4 h-[320px] w-[272px] origin-left scale-90 select-none overflow-clip rounded-xl bg-white/50 sm:float-right sm:ml-8 sm:scale-100"
			>
				<img src={anne} class="object-contain" alt="Anne Dyke's headshot" />
			</div>

			<p class="pb-4">
				A native of North Carolina, Anne is a professional flutist who performs and teaches in the
				Raleigh area. Her resume includes teaching lessons to beginning, intermediate and advanced
				students. She enjoys teaching and helping her students build confidence in their ability.
				She maintains a large flute studio and her students consistently place into All-State,
				All-District and All-County bands, as well as the local Triangle Youth Philharmonic,
				Symphony and Orchestra programs. She also teaches beginning to intermediate piano students
				at KinderVillage in Cary, NC as well as her home studio.
			</p>

			<p class="pb-4">
				Anne holds degrees from Florida State University (Doctorate of Music), University of
				Illinois (Master of Music), and the University of North Carolina at Chapel Hill (Bachelor of
				Music Education), where she studied with Charles DeLaney, Alex Murray and Brooks de Wetter
				Smith. After her Master's degree, she moved to Chicago to study with Walfrid Kujala, former
				piccoloist of the Chicago Symphony Orchestra, where she studied orchestral and solo
				repertoire in depth.
			</p>

			<div
				class="float-none mb-4 h-[320px] w-[235px] origin-left scale-90 select-none overflow-clip rounded-xl bg-white/50 sm:float-left sm:mr-8 sm:scale-100"
			>
				<img src={anne2} class="object-contain" alt="Anne Dyke with her flute and piano" />
			</div>

			<p class="pb-4">
				In addition to teaching at her home studio, Anne was also Adjunct Flute Instructor at UNC-CH
				from 2000-2005 teaching music majors, minors and non-majors. She also served as Interim
				Flute Instructor teaching and performing with the faculty woodwind quintet in 2005 for
				Brooks de Wetter Smith during his sabbatical. She held Adjunct positions at Shaw University
				(teaching flute) and Wake Technical Community College (teaching music appreciation classes).
				She has also taught band, strings and general music in public and private schools in North
				Carolina, Illinois and Texas.
			</p>

			<p class="pb-4">
				For three years, Anne was a substitute in the North Carolina Symphony. She attended the
				Aspen Music Festival and won the National Flute Association Orchestral Masterclass with
				Bernard Goldberg in 1989 in New Orleans. She currently serves on the Board of Directors of
				the Raleigh Area Flute Association and founded of the yearly Solofest Contest which is very
				popular and has over 125 flutists participate.
			</p>

			<p class="pb-4">
				Subscribe and check out her Youtube channel, <a
					class="font-semibold underline underline-offset-2"
					href="https://www.youtube.com/@AnneDykeFlute/videos"
					target="_blank">Anne Dyke Flute</a
				>
				and play a duet with her!
				<img src={note} alt="" class="pointer-events-none inline w-6 rotate-3 select-none" />
			</p>
		</section>
	</main>
</div>
