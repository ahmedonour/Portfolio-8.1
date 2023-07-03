<script>
	import DarkMode from './DarkMode.svelte';
</script>

<svelte:head>
	<title>Ahmed Suliman | Web Developer & Designer</title>
</svelte:head>
<nav>
	<div class="logo">
		<h1>as</h1>
	</div>
	<div class="nav-btn">
		<div class="icons">
			<DarkMode />
			<i class="fab fa-github" />
			<i class="fab fa-twitter" />
			<i class="fab fa-facebook" />
		</div>
		<p>Let's Talk</p>
	</div>
</nav>

<style>
	:global(body) {
		background-color: #f2eee2;
		color: #ffffff;
		transition: background-color 0.3s;
	}
	:global(body.dark-mode) {
		background-color: #343434;
		color: #ffffff;
	}
	:global(body.dark-mode) h1 {
		color: #ffffff;
	}
	:global(body.dark-mode) p {
		color: #ffffff;
	}
	:global(body.dark-mode) i {
		color: #ffffff;
	}
	* {
		padding: 0;
		margin: 0;
		box-sizing: border-box;
	}
	.logo h1 {
		text-transform: uppercase;
		font-family: var(--ff-logo);
		font-size: 4rem;
		font-weight: 400;
	}
	nav {
		color: var(--clr-gray);
		width: 64.125rem;
		height: 5rem;
		font-family: var(--ff-main);
		display: flex;
		justify-content: space-between;
		align-items: center;
	}
	nav .nav-btn {
		width: 30rem;
		height: 3.125rem;
		display: flex;
		padding: 0rem 0.125rem 0rem 2rem;
		justify-content: flex-end;
		align-items: center;
		gap: 1.875rem;
	}
	nav .nav-btn .icons {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		align-items: center;
		gap: 1.875rem;
	}
	nav .nav-btn .icons i {
		font-size: 2rem;
	}
	nav .nav-btn p {
		font-family: var(--ff-main);
		font-weight: 400;
		font-size: 2rem;
	}
</style>
