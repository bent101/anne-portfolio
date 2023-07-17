<script lang="ts">
	export let href = "";
	export let icon = "";
</script>

<a
	{href}
	target="_blank"
	class="rounded-full p-2 w-14 h-14 bg-white hover:scale-105 transition-transform duration-300"
>
	<img src={icon} class="pointer-events-none select-none object-contain aspect-square" alt="" />
</a>
