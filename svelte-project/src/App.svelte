<script>
	let firstName = '';
	let lastName = '';
	$: fullName = `${firstName} ${lastName}`
</script>

<main>
	<input placeholder='Enter your name' bind:value={firstName}>
	<input placeholder='Enter your name' bind:value={lastName}>
	<div>Hello,{fullName}</div>
</main>

<style>
</style>