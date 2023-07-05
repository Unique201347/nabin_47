<script>
	import '../app.css';
	import PageTransition from './ransition.svelte';

	export let data;
</script>

<PageTransition url={data.url}>
	<slot />
</PageTransition>
