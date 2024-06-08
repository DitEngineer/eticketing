<div class="box">
	<p>Total price</p>
	<span class="details"
		><p class="total-price">100.00€</p>
		<p class="num-of-tickets">4 tickets</p></span
	>
	<button class="checkout-btn">Checkout</button>
</div>

<style>
	* {
		padding: 0;
		margin: 0;

		box-sizing: border-box;
	}

	.box {
		position: fixed;
		bottom: 0;
		left: 0;

		height: max-content;
		width: 100%;

		padding: 8px 16px;

		border-top: 1px solid #dcdcdc;

		background-color: #fff;
	}

	.details {
		height: max-content;
		width: max-content;

		display: flex;
		align-items: center;
		gap: 6px;
	}

	.box p {
		color: #999;
	}

	.details .total-price {
		font-size: 18px;
		font-weight: 500;
		color: #000;
	}

	.num-of-tickets {
		font-size: 14px;
	}

	.checkout-btn {
		height: max-content;
		width: max-content;

		position: absolute;
		top: 50%;
		transform: translateY(-50%);
		right: 16px;

		padding: 8px 16px;

		background-color: #252525;
		color: #fff;

		border: none;
		outline: none;

		border-radius: 5px;
	}
</style>
