<div class="box">
	<div class="heading">
		<p class="nav">Prev</p>
		<p>Package</p>
		<p class="nav">Next</p>
	</div>

	<p class="package-details-heading">Details</p>

	<p class="description">
		Best package you can buy, it comes with additional free drinks, premium bracelets and with the
		best seating plan to make this night all yours.
	</p>

	<div class="selection-box">
		<p class="price">€24.99</p>
		<div class="counter">
			<button class="sub-btn">-</button>
			<p>0</p>
			<button class="add-btn">+</button>
		</div>
	</div>
</div>

<style>
	* {
		padding: 0;
		margin: 0;

		box-sizing: border-box;
	}

	.box {
		height: max-content;
		min-height: max-content;
		width: 100%;

		display: flex;
		flex-direction: column;
		gap: 8px;

		padding: 8px;

		border-radius: 10px;

		outline: 1px solid #dcdcdc;
	}

	.heading {
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	.nav {
		font-size: 14px !important;
		font-weight: 400 !important;
	}

	.heading p {
		font-size: 16px;
		font-weight: 500;
	}

	.package-details-heading {
		font-weight: 500;
		margin-bottom: -4px;
	}

	.description {
		font-size: 14px;
		color: #999;
	}

	.selection-box {
		border-top: 2px dashed #f3f3f3;

		height: max-content;
		width: 100%;

		padding: 8px 0;

		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	.price {
		font-weight: 500;
	}

	.counter {
		height: max-content;
		width: max-content;

		display: flex;
		justify-content: space-between;
		align-items: center;
		gap: 8px;

		padding: 3px 4px;

		background-color: #f3f3f3;

		border-radius: 15px;
	}

	.sub-btn,
	.add-btn {
		height: 20px;
		width: 20px;

		border-radius: 50%;

		border: none;

		outline: 1px solid #dcdcdc;

		background-color: #fff;

		font-weight: 500;
	}
</style>
