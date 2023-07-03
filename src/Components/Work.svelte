<div class="work_Section">
	<h1>Work</h1>
	<div class="showCase">
		<!-- svelte-ignore a11y-missing-attribute -->
		<!-- <img src="https://images.pexels.com/photos/62689/pexels-photo-62689.jpeg" /> -->
		<!-- svelte-ignore a11y-missing-attribute -->
		<!-- <img src="https://images.pexels.com/photos/57690/pexels-photo-57690.jpeg" /> -->
		<div class="imges" />
		<div class="imges" />
	</div>
</div>

<style>
	:global(body.dark-mode) h1 {
		color: #ffffff;
	}
	:global(body.dark-mode) p {
		color: #ffffff;
	}
	:global(body.dark-mode) i {
		color: #ffffff;
	}
	.work_Section {
		width: 932px;
		height: 320px;
	}
	h1 {
		color: var(--clr-gray);
		font-size: 8rem;
		font-family: M PLUS Code Latin;
		font-style: normal;
		font-weight: 700;
		line-height: normal;
	}
	.work_Section .showCase {
		width: 1028px;
		height: 500px;
		display: flex;
		align-items: flex-start;
		gap: 1.75rem;
	}
	.work_Section .showCase .imges:nth-child(1) {
		width: 31.25rem;
		height: 31.25rem;

		border-radius: 0.9375rem;
		background: url(https://images.pexels.com/photos/57690/pexels-photo-57690.jpeg),
			lightgray no-repeat;
		background-size: cover;
		/* important to override inline style */
	}
	.work_Section .showCase .imges:nth-child(2) {
		width: 31.25rem;
		height: 31.25rem;
		border-radius: 0.9375rem;
		background: url(https://images.pexels.com/photos/2657669/pexels-photo-2657669.jpeg),
			lightgray no-repeat;
		background-size: cover;
		/* important to override inline style */
	}
</style>
