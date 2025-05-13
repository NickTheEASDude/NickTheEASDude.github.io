<svelte:head>
	<title>I'm tired...</title>
</svelte:head>

<script lang="ts">
	import frisbee from "$lib/assets/frisbee.png";
	import allcode from "$lib/assets/allcode.mp4";
	import raspi from "$lib/assets/raspi.mp4";
	
</script>
<main class="outlined">
	<h2>Here is a frisbee I spent a month designing.</h2>
	<div class="edges">
		<div class="middle">
			<img src={ frisbee } alt="FRISBEEEEEEEEEEEEEEEEE"/>
		</div>
	</div>
	<br style="height: 25px;"/>
	<hr/>
	<h2>A raspberry pi I set up as well &#40this took forever...&#41</h2>
	<div class="edges">
		<div class="middle">
			<video muted autoplay loop width=720px height=405px>
				<source src={ raspi } type="video/mp4"/>
				No video support in browser.
			</video>
		</div>
	</div>
	<br style="height: 25px;"/>
	<hr/>
	<h2>Finally, a bluetooth robot called Formula AllCode. This was a bit of a pain, because of the way it connects to bluetooth on Linux.</h2>
	<div class="edges">
		<div class="middle">
			<video muted autoplay loop width=720px height=405px>
				<source src={ allcode } type="video/mp4"/>
				No video support in browser.
			</video>
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
		padding: 0px;
	}

	video, img {
		display: block;
	}
</style>
