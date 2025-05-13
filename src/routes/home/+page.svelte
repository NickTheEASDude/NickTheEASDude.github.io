<svelte:head>
	<title>I'm tired...</title>
</svelte:head>

<script lang="ts">
	import frisbee from "$imports/frisbee.png";
</script>
<main class="outlined">
	<div class="edges">
		<div class="middle">
			<div class="bg edges">
				<img src={ frisbee } alt="FRISBEEEEEEEEEEEEEEEEE"/>
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
