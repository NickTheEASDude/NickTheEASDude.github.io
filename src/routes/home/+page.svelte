<svelte:head>
	<title>I'm tired...</title>
</svelte:head>

<script lang="ts">
	import { onMount } from "svelte";

	let finalCanvas: HTMLCanvasElement;

	onMount(() => {
		let ctx : any = finalCanvas.getContext("2d");
		ctx.strokeStyle = "#0000FF";
		ctx.moveTo(0,0);
		ctx.lineTo(200,100);
		ctx.stroke();
	});
</script>



<main>
	<h3>Hello. How are you?</h3>
	<h2>I am under the water.</h2>
	<h2>Please help me, here too much raining,</h2>
	<h1>Woooooooo!</h1>
	
	<canvas bind:this={ finalCanvas } width="200" height="100"></canvas>
</main>

<style>
	canvas {
		border: 1px solid black;
	}
</style>