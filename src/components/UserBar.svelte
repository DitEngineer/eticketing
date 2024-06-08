<script>
	import UserIcon from '../components/UserIcon.svelte';
</script>

<div class="wrapper">
	<UserIcon />

	<div class="box">
		<p>Good morning</p>
		<p>User name</p>
	</div>

	<div class="quick-action">
		<button>
			<svg
				id="Notification"
				width="22px"
				height="22px"
				viewBox="0 0 24 24"
				fill="none"
				xmlns="http://www.w3.org/2000/svg"
			>
				<path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M11.9961 2.51416C7.56185 2.51416 5.63519 6.5294 5.63519 9.18368C5.63519 11.1675 5.92281 10.5837 4.82471 13.0037C3.48376 16.4523 8.87614 17.8618 11.9961 17.8618C15.1152 17.8618 20.5076 16.4523 19.1676 13.0037C18.0695 10.5837 18.3571 11.1675 18.3571 9.18368C18.3571 6.5294 16.4295 2.51416 11.9961 2.51416Z"
					stroke="black"
					stroke-width="1.5"
					stroke-linecap="round"
					stroke-linejoin="round"
				/>
				<path
					d="M14.3059 20.5122C13.0116 21.9579 10.9926 21.9751 9.68591 20.5122"
					stroke="black"
					stroke-width="1.5"
					stroke-linecap="round"
					stroke-linejoin="round"
				/>
			</svg></button
		>
		<button>
			<svg
				id="Heart"
				width="22px"
				height="22px"
				viewBox="0 0 26 24"
				fill="none"
				xmlns="http://www.w3.org/2000/svg"
			>
				<path
					d="M21.4999 9.63556C21.49 7.09969 20.1596 4.71489 17.5366 3.86991C15.7355 3.28869 13.7736 3.61191 12.25 5.79939C10.7264 3.61191 8.76447 3.28869 6.96339 3.86991C4.34014 4.71498 3.00971 7.10024 3.00008 9.63643C2.97582 14.6801 8.08662 18.5397 12.2487 20.3844L12.25 20.3838L12.2513 20.3844C16.4136 18.5396 21.5248 14.6797 21.4999 9.63556Z"
					stroke="black"
					stroke-width="1.5"
					stroke-linecap="square"
				/>
			</svg>
		</button>
	</div>
</div>

<style>
	* {
		padding: 0;
		margin: 0;

		box-sizing: border-box;
	}
	.wrapper {
		height: max-content;
		width: 100%;

		display: flex;
		justify-content: space-between;
		align-items: center;
		gap: 8px;
	}

	.box {
		height: max-content;
		width: calc(100% - 32px - 32px - 32px - 8px - 6px - 16px);

		display: flex;
		flex-direction: column;
		gap: 0px;
	}

	.box p:first-child {
		font-size: 12px;
	}

	.box p:nth-child(2) {
		font-size: 14px;
		font-weight: 500;
	}

	.quick-action {
		height: max-content;
		width: max-content;

		display: flex;
		gap: 8px;
	}

	.quick-action button {
		height: 32px;
		width: 32px;

		display: flex;
		justify-content: center;
		align-items: center;

		border-radius: 50%;

		border: none;
		outline: 1px solid #dcdcdc;
		background-color: transparent;
	}
</style>
