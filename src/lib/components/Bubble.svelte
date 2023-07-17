<script lang="ts">
	export let href = "";
	export let icon = "";
</script>

<a
	{href}
	target="_blank"
	class="rounded-full p-2 w-14 h-14 bg-white/50 hover:bg-white hover:scale-105 transition-all duration-300"
>
	<img src={icon} class=" object-contain aspect-square" alt="" />
</a>
