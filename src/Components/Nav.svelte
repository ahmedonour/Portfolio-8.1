<script>
    export let title = "Ahmed Suliman"
</script>
<svelte:head>
    <title>
        Ahmed Suliman | Web Developer & Designer
    </title>
</svelte:head>
<nav>
	<div class="logo">
		<h1>as</h1>
	</div>
	<div class="nav-btn">
		<div class="icons">
			<i class="fas fa-adjust"></i>
            <i class="fab fa-github"></i>
            <i class="fab fa-twitter"></i>
            <i class="fab fa-facebook"></i>
		</div>
		<p>Let's Talk</p>
	</div>
</nav>

<style>
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
    nav .nav-btn .icons{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        gap: 1.875rem;
    }
    nav .nav-btn .icons i{
        font-size: 2rem;
    }
	nav .nav-btn p {
		font-family: var(--ff-main);
		font-weight: 400;
		font-size: 2rem;
	}
</style>
