<script>
	import { fly } from 'svelte/transition';
</script>

<div class="hero">
	<h1 transition:fly={{ y: 200, duration: 2000, delay: 1 }}>Hi</h1>

	<p>
		There, my name is Ahmed Suliman and I am a skilled web developer who specializes in creating
		portfolios for businesses and individuals. With a passion for coding and a keen eye for design,
		I take pride in delivering high-quality websites that are not only visually appealing but also
		user-friendly and functional.
	</p>
</div>

<style>
	:global(body.dark-mode) h1 {
		color: #ffffff;
	}
	:global(body.dark-mode) p {
		color: #ffffff;
	}

	.hero {
		width: 932px;
		height: 320px;
		display: inline-flex;
		padding: 5.5625rem 2.8125rem;
		align-items: center;
		gap: 7.8125rem;
	}
	.hero h1 {
		color: var(--clr-gray);
		font-size: 8rem;
		font-family: var(--ff-main);
		font-style: normal;
		font-weight: 700;
		line-height: normal;
	}
	.hero p {
		color: var(--clr-gray);
		display: flex;
		width: 42.4375rem;
		flex-direction: column;
		text-align: justify;
		font-size: 2rem;
		font-family: var(--ff-main);
		font-style: normal;
		font-weight: 400;
		line-height: normal;
	}
</style>
