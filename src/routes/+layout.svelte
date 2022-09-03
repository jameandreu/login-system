<script lang="ts">
</script>

<slot />

<style lang="scss">
	:global {
		@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap');

		*,
		*::before,
		*::after {
			margin: 0;
			padding: 0;
			box-sizing: border-box;
		}
		::-webkit-scrollbar {
			width: 4px;
			height: 4px;
		}
		::-webkit-scrollbar-track {
			background-color: transparent;
		}

		::-webkit-scrollbar-thumb {
			background-color: var(--color-brand);
			border-radius: var(--radius-base);
		}
		:root {
			--font-serif: 'Inter', sans-serif;
		}
		html,
		body {
			height: 100vh;
			font-family: var(--font-serif);
			background-color: pink;
			.someDiv {
				height: 100%;
				display: flex;
				justify-content: space-between;
				align-items: center;

				border: 1px solid red;
				&__insideDiv {
					width: 3rem;
					height: 2rem;
					background-color: aqua;
				}
			}
		}
	}
</style>
