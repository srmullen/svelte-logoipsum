<script>
	import * as Logos from 'svelte-logoipsum';

	const logos = [];
	for (let i = 1; i <= 26; i++) {
		const name = `Logo${i}`;
		logos.push({ name: `<${name} />` , component: Logos[name] });
	}
</script>

<main>
	<h1>svelte-logoipsum</h1>
	<div class="logos">
		{#each logos as logo}
			<div class="logo">
				<span>{logo.name}</span>
				<div>
					<svelte:component this={logo.component} />
				</div>
			</div>
		{/each}
	</div>
</main>

<style>
	main {
		margin: 0 auto;
	}

	h1 {
		text-align: center;
	}

	.logos {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
		display: flex;
		flex-wrap: wrap;
		justify-content: space-around;
	}

	.logo {
		border: 1px solid black;
		margin: 1.5rem 0;
		min-width: 240px;
		margin: 12px;
		padding: 24px;
		border-radius: 6px;
		
	}

	.logo span {
		display: block;
		margin-bottom: 1rem;
	}

	@media (min-width: 640px) {
		main {
			max-width: 500px;
		}
	}

	@media (min-width: 1024px) {
		main {
			max-width: 800px;
		}
	}

	@media (min-width: 1280px) {
		main {
			max-width: 1000px;
		}
	}

	@media (min-width: 1280px) {
		main {
			max-width: 1000px;
		}
	}
</style>