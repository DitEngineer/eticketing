<div class="wrapper">
	<div class="icon"></div>
	<div class="details">
		<p class="name">Organisator name</p>
		<p class="upcoming-events">6 upcoming events</p>
	</div>
	<button class="flw-btn">Follow</button>
</div>

<style>
	* {
		padding: 0;
		margin: 0;

		box-sizing: border-box;
	}

	.wrapper {
		position: relative;

		height: max-content;
		width: 100%;

		padding: 8px;

		display: flex;
		align-items: center;
		gap: 4px;

		background-color: #f2f2f2;

		outline: 1px solid #dcdcdc;

		border-radius: 10px;
	}

	.icon {
		height: 40px;
		width: 40px;

		border-radius: 50%;

		background-color: #000;
	}

	.details {
		height: max-content;
		width: max-content;

		display: flex;
		flex-direction: column;
		gap: 0px;
	}

	.name {
		font-size: 16px;
		font-weight: 500;
	}

	.upcoming-events {
		font-size: 14px;
	}

	.flw-btn {
		position: absolute;
		right: 8px;

		height: max-content;
		width: max-content;

		padding: 4px 8px;

		border-radius: 5px;

		border: none;

		outline: 2px solid #4ead43;

		color: #4ead43;

		font-weight: 600;
	}
</style>
