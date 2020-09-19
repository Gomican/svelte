<script>
	import Greeting from './Greeting.svelte'

	const messages = ['Hello!', 'Svelte!'];
	let current = 0;

	const toggle = () => current = (current+1) % 2;
</script>

<main>
	<Greeting userName='Gmican' />
	{messages[current]}
	<button on:click={toggle}>Toggle Message</button>
</main>

<style>
</style>