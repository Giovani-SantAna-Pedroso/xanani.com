<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>



<svelte:head>
	<link rel="icon" href={favicon} />
  <link
    rel="stylesheet"
    href="https://fonts.googleapis.com/css2?family=Oswald:wght@300;400;500;600;700&display=swap"
  />
</svelte:head>

{@render children?.()}
