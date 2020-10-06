<script>
	import Card from '../shared/Card.svelte';
</script>

<style lang="postcss">
	.btn {
		border: 0;
		cursor: pointer;
		border-radius: 6px;
		padding: 8px 12px;
		font-weight: bold;
		box-shadow: 1px 2px 3px rgba(0, 0, 0, 0.2);
	}

	.center {
		text-align: center;
	}

	.space {
		margin-top: 30px;
		margin-bottom: 30px;
	}

	.test-class {
		text-transform: uppercase;
		font-weight: bold;
	}
</style>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<div class="center">
	<Card>
		<h1 class="test-class">Sapper Boilerplate</h1>
		<h2>with PostCSS</h2>
	</Card>
	<div class="space">
	</div>
</div>