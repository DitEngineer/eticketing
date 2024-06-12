<script>
	import CategoryTag from '../components/CategoryTag.svelte';
	import InfoTag from '../components/InfoTag.svelte';
	import OrganisatorBar from '../components/OrganisatorBar.svelte';
	import TicketReservation from '../components/TicketReservation.svelte';
	import TotalBox from '../components/TotalBox.svelte';
</script>

<div class="container">
	<nav>
		<button
			><svg
				id="Arrow - Left"
				width="22px"
				height="22px"
				viewBox="0 0 26 24"
				fill="none"
				xmlns="http://www.w3.org/2000/svg"
			>
				<path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M20.5 12.75L4.59976 12.75L4.59976 11.25L20.5 11.25L20.5 12.75Z"
					fill="black"
				/>
				<path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M11.8605 5.97777L5.81272 12.0005L11.8605 18.0223L10.8021 19.0852L3.68691 12.0006L10.802 4.91492L11.8605 5.97777Z"
					fill="black"
				/>
			</svg></button
		>
		<p>Event Details</p>
		<button>
			<svg
				id="Upload"
				width="20px"
				height="20px"
				viewBox="0 0 24 24"
				version="1.1"
				xmlns="http://www.w3.org/2000/svg"
				xmlns:xlink="http://www.w3.org/1999/xlink"
			>
				<title>Iconly/Light-Outline/Upload</title>
				<g
					id="Iconly/Light-Outline/Upload"
					stroke="none"
					stroke-width="1"
					fill="none"
					fill-rule="evenodd"
				>
					<g id="Upload" transform="translate(2.000000, 2.000000)" fill="#000000">
						<path
							d="M5.3684,6.7941 C5.7824,6.7941 6.1184,7.1301 6.1184,7.5441 C6.1184,7.9581 5.7824,8.2941 5.3684,8.2941 L4.4354,8.2941 C2.8164,8.2941 1.5004,9.6101 1.5004,11.2281 L1.5004,16.1031 C1.5004,17.7221 2.8164,19.0381 4.4354,19.0381 L15.5654,19.0381 C17.1834,19.0381 18.5004,17.7221 18.5004,16.1031 L18.5004,11.2191 C18.5004,9.6061 17.1884,8.2941 15.5764,8.2941 L14.6334,8.2941 C14.2194,8.2941 13.8834,7.9581 13.8834,7.5441 C13.8834,7.1301 14.2194,6.7941 14.6334,6.7941 L15.5764,6.7941 C18.0154,6.7941 20.0004,8.7791 20.0004,11.2191 L20.0004,16.1031 C20.0004,18.5491 18.0104,20.5381 15.5654,20.5381 L4.4354,20.5381 C1.9904,20.5381 0.0004,18.5491 0.0004,16.1031 L0.0004,11.2281 C0.0004,8.7831 1.9904,6.7941 4.4354,6.7941 L5.3684,6.7941 Z M10.531,0.2217 L13.447,3.1497 C13.739,3.4437 13.738,3.9177 13.445,4.2097 C13.151,4.5017 12.677,4.5017 12.385,4.2077 L10.7494,2.56645 L10.75,13.541 L9.25,13.541 L9.2494,2.56645 L7.616,4.2077 C7.47,4.3557 7.277,4.4287 7.085,4.4287 C6.894,4.4287 6.702,4.3557 6.556,4.2097 C6.263,3.9177 6.261,3.4437 6.554,3.1497 L9.469,0.2217 C9.75,-0.0613 10.25,-0.0613 10.531,0.2217 Z"
							id="Combined-Shape"
						></path>
					</g>
				</g>
			</svg>
		</button>
	</nav>
	<div class="cover"></div>
	<div class="info-area">
		<span class="heading">
			<CategoryTag />
			<button class="fvt-btn">
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
		</span>
		<h1>Happy Holiday Music Concert Festival Indonesia Region</h1>
		<p class="description">
			The air buzzed with excitement as the Happy Holiday Music Concert Festival kicked off in Indonesia’s tropical paradise.
		</p>
		<InfoTag bgColor="transparent" padding="0" iconSize="18px" fontSize="14px" />
		<OrganisatorBar />
		<h4>Available tickets</h4>
		<TicketReservation />
		<TotalBox />
	</div>
</div>

<style>
	* {
		padding: 0;
		margin: 0;

		box-sizing: border-box;
	}

	.container {
		height: auto;
		width: 100%;

		background-color: #fff;

		display: flex;
		flex-direction: column;

		overflow: auto;
	}

	nav {
		position: fixed;
		top: 0;
		left: 0;

		height: max-content;
		width: 100%;

		padding: 16px;

		display: flex;
		justify-content: space-between;
		align-items: center;

		font-weight: 500;
		color: #fff;
	}

	nav button {
		height: 32px;
		width: 32px;

		display: flex;
		justify-content: center;
		align-items: center;

		border-radius: 50%;

		border: none;
		outline: none;

		background-color: #fff;
	}

	.cover {
		height: 240px;
		width: 100%;

		background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.1)), url('cover-test.jpg');
		background-position: cover;
		background-repeat: no-repeat;
		background-size: cover;
	}

	.info-area {
		margin-top: -16px;

		height: auto;
		max-height: 70%;
		width: 100%;

		background-color: #fff;

		display: flex;
		flex-direction: column;
		gap: 16px;

		padding: 16px;

		outline: 1px solid #dcdcdc;

		border-radius: 10px 10px 0 0;

		overflow-y: auto;

		padding-bottom: 80px;
	}

	.heading {
		height: max-content;
		width: 100%;

		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	.description{
		color: #999;
	}

	.fvt-btn {
		height: 32px;
		width: 32px;

		display: flex;
		justify-content: center;
		align-items: center;

		border-radius: 8px;

		border: none;
		outline: 1px solid #dcdcdc;
	}

	h1 {
		font-size: 20px;
	}

	h4 {
		margin-bottom: -8px;
	}
</style>
