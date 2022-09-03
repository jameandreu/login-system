<div class="component">
	<div class="component__inside">some other text here</div>
</div>

<style lang="scss">
	.component {
		height: 20rem;
		width: 30rem;
		background-color: red;
		display: flex;
		justify-content: center;
		align-items: center;
		&__inside {
			height: 10rem;
			width: 20rem;
			background-color: aqua;
			text-align: center;
		}
	}
</style>
