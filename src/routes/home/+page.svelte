<svelte:head>
	<title>I'm tired...</title>
</svelte:head>

<script lang="ts">
	import fire from "./fire.png";
</script>
<main class="outlined">
	<h3>Hello. How are you?</h3>
	<h2>I am under the water.</h2>
	<h2>Please help me, here too much raining,</h2>
	<h1>Woooooooo!</h1>
	
	<div class="edges">
		<div class="middle">
			<div class="bg edges">
				<img src={ fire } alt="FIYAAAAAAAAAAA"/>
			</div>
		</div>
	</div>
	<br style="height: 25px;"/>
	<div class="edges">
		<div class="middle">
			<div class="bg edges" style=" width: 900px; height: 600px;"></div>
		</div>
	</div>
</main>

<style>
	div {
		width: fit-content;
		height: fit-content;
	}
	div.edges {
		border: 1px solid white;
	}
	div.middle {
		border: 3px solid black;
	}
	div.bg {
		background-image: url("brick.png");
	}
</style>
