<script>
	function toggle() {
		window.document.body.classList.toggle('dark-mode');
	}
</script>

<button on:click={toggle}>
	<i class="fas fa-adjust" />
	<slot />
</button>

<style>
	button {
		background-color: transparent;
		color: #343434;
		border: none;
		border-radius: 4px;
		/* padding: 0.5rem; */
		font-size: 2rem;
		text-transform: uppercase;
		cursor: pointer;
	}
	:global(body.dark-mode) button {
		color: white;
	}
</style>
