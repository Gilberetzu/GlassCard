<script>
	import FloatingCard from "./FloatingCard.svelte";
</script>

<div class="cardHolder">
	<FloatingCard/>
	<FloatingCard/>
	<FloatingCard/>
	<FloatingCard/>
	<FloatingCard/>
	<FloatingCard/>
</div>

<style>
	.cardHolder{
		padding: 100px;
		display: inline-grid;
		gap: 10px;
		grid-template-areas: 'a a a'
							 'a a a';
	}
</style>