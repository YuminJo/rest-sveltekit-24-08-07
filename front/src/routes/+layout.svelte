<script lang="ts">
	import '$lib/app.css';

	const { children } = $props();
</script>

<header>헤더</header>
<main>{@render children()}</main>
<footer>푸터</footer>
