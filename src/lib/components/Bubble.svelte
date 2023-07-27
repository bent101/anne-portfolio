<script lang="ts">
	export let href = "";
	export let icon = "";
</script>

<a
	{href}
	target="_blank"
	class="inline-block h-12 w-12 rounded-full bg-white/50 p-2 transition-all duration-300 hover:scale-105 hover:bg-white"
>
	<img src={icon} class="pointer-events-none aspect-square select-none object-contain" alt="" />
</a>
