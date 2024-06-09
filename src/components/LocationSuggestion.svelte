<script>
	import InfoTag from "./InfoTag.svelte";

</script>

<p class="head-text">Based on your location</p>
<div class="card">
    <div class="img-area"></div>
    <InfoTag/>
    <div class="heading-area">
		<p>Happy Holiday Music Concert Indonesia Region</p>
	</div>
	<div class="wrapper">
		<div class="icon"></div>
		<p>Name</p>
	</div>
	<div class="action-area">
		<button class="booking-btn">Booking</button>
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
	</div>
</div>

<style>
    *{
        padding: 0;
        margin: 0;

        box-sizing: border-box;
    }

	.head-text{
		color: #000;
		font-size: 16px;

		margin-bottom: -8px;
	}

    p{
        font-weight: 500;
		color: #000;
    }

    .card{
        height: max-content;
        width: 100%;

        padding: 8px;

        display: flex;
        flex-direction: column;
        gap: 8px;

        border-radius: 10px;

        outline: 1px solid #f3f3f3;
    }

    .img-area{
        height: 120px;
        width: 100%;

        border-radius: 5px;

        background-image: url("cover-test2.jpg");
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }

    .heading-area p {
		font-weight: 500;
		color: #000;
	}

	.wrapper {
		height: max-content;
		width: 100%;

		display: flex;
		align-items: center;
		gap: 4px;
	}

	.icon {
		height: 16px;
		width: 16px;

		border-radius: 50%;

		background-color: #252525;
	}

	p {
		font-size: 14px;

		color: #999;
	}

	.action-area {
		height: 40px;
		width: 100%;

		display: flex;
		justify-content: space-between;
	}

	.booking-btn {
		height: 40px;
		width: calc(100% - 8px - 40px);

		border-radius: 10px;

		border: none;
		outline: 1px solid #dcdcdc;
	}

	.fvt-btn {
		height: 40px;
		width: 40px;

		display: flex;
		justify-content: center;
		align-items: center;

		border-radius: 8px;

		border: none;
		outline: 1px solid #dcdcdc;
	}
</style>