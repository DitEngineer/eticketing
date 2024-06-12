<div class="container">
	<div class="cover"></div>
	<div class="info">
		<p class="name">Name</p>
		<p class="date">1.2.2025.</p>
		<p class="location">KGB, Maribor</p>
        <p class="price">From 25.00€</p>
	</div>
</div>

<style>
	* {
		padding: 0;
		margin: 0;

		box-sizing: border-box;
	}

	.container {
		height: max-content;
		width: 100%;

		padding: 8px;

		background-color: #fff;

		display: flex;
		justify-content: space-between;
		align-items: flex-start;
		gap: 16px;

		border-radius: 5px;

		outline: 1px solid #f3f3f3;
	}

	.cover {
		height: 72px;
		width: 35%;

        background-image: url("cover-test.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;

		border-radius: 5px;

		outline: 1px solid #dcdcdc;
	}

	.info {
        position: relative;

        z-index: 0;

		height: 72px;
		width: 65%;
	}

	.name {
		font-weight: 500;
	}

    .date, .location{
        font-size: 14px;

        color: #999;
    }

    .price{
        position: absolute;
        bottom: 0;
        right: 0;

        font-size: 14px;

        font-weight: 500;
    }
</style>
