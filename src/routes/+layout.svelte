<script>
	import '../app.css';

	let { children } = $props();
</script>

<div class="prose prose-xl px-10 py-20">{@render children()}</div>
