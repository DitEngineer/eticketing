<script>
	import Notification from "../components/Notification.svelte";

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
		<h1>Notifications</h1>
		<button>
			<svg xmlns="http://www.w3.org/2000/svg" height="16px" viewBox="0 0 128 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M64 360a56 56 0 1 0 0 112 56 56 0 1 0 0-112zm0-160a56 56 0 1 0 0 112 56 56 0 1 0 0-112zM120 96A56 56 0 1 0 8 96a56 56 0 1 0 112 0z"/></svg>
		</button>
	</nav>

	<p class="date">21 November, 2024</p>
	<Notification heading="Payment successful!" description="You have successfully made a payment."/>
	<p class="date">21 November, 2024</p>
	<Notification heading="Payment rejected!" description="Your payment has been rejected. Please try again."/>
	<p class="date">21 November, 2024</p>
	<Notification heading="All set up!" description="Welcome to eVenue!"/>
	<p class="date">21 November, 2024</p>
	<Notification heading="Email confirmation" description="In orderd to finish account creation, confirm your email."/>
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

		padding: 80px 16px 16px 16px;

		background-color: #fff;

		display: flex;
		flex-direction: column;

		gap: 24px;

		padding-bottom: 65px;
	}

	h1{
		font-size: 20px;
		font-weight: 500;
		color: #000;
	}

	.date{
		font-size: 16px;
		color: #999;
		font-weight: 500;
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

		background-color: #fff;

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
		outline: 1px solid #dcdcdc;

		background-color: #fff;
	}
</style>