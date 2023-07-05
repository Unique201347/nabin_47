<script>
	import '../app.css';
	import ThemeSwitch from '../lib/components/ThemeSwitch.svelte';
	import PageTransition from './ransition.svelte';

	export let data;
</script>

<ThemeSwitch />

<PageTransition url={data.url}>
	<slot />
</PageTransition>
