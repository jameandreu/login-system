<script>
	import Component from './Component.svelte';
	let count = 0;
	const increment = function () {
		count++;
		console.log(count);
	};
	const disappear = function () {};
</script>

<div class="someDiv">
	some text here
	<div class="someDiv__insideDiv" />
</div>
<Component />

<button class="btn" on:click={increment}> Disappear! </button>
