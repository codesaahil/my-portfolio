<script lang="ts">
	let { id, children } = $props();
</script>

<section
	{id}
	class="flex min-h-screen flex-col items-center justify-center bg-gradient-to-b from-green-100 via-green-200 to-green-50 px-6 text-center"
>
	{@render children()}
</section>
