<script>
	let showButton = false;
</script>

{showButton}
<h1 class={showButton ? 'bg-red-800' : 'bg-yellow-800'}>Welcome to SvelteKit</h1>
<button on:click={() => (showButton = !showButton)}>toggle</button>
