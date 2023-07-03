<script>
	import Hero from '../Components/Hero.svelte';
	import Nav from '../Components/Nav.svelte';
	import Work from '../Components/Work.svelte';
</script>

<main>
	<Nav />
	<Hero />
	<Work />
</main>

<style>
	:root {
		--ff-main: 'M PLUS Code Latin', sans-serif;
		--ff-logo: 'Plaster', cursive;

		--clr-gray: #343434;
		--clr-black: #000;
		--clr-white: #fff;
	}

	* {
		padding: 0;
		margin: 0;
		box-sizing: border-box;
	}

	/* main{
        display: grid;
        place-items: center;
        width: 50%;
    } */
</style>
