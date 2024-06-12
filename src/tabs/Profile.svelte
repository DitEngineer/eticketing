<script>
	import UserIcon from "../components/UserIcon.svelte";
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
		<h1>My Profile</h1>
        <button>
<svg id="Setting"width="20px" height="20px" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <title>Iconly/Bold/Setting</title>
    <g id="Iconly/Bold/Setting" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
        <g id="Setting" transform="translate(2.499897, 2.000100)" fill="#000000" fill-rule="nonzero">
            <path d="M10.217226,0 C10.9734745,0 11.6581859,0.42 12.0363101,1.04 C12.2202625,1.34 12.3428973,1.71 12.3122386,2.1 C12.2917995,2.4 12.3837756,2.7 12.5472888,2.98 C13.0684871,3.83 14.2232989,4.15 15.1226214,3.67 C16.1343592,3.09 17.411806,3.44 17.9943217,4.43 L17.9943217,4.43 L18.6790331,5.61 C19.2717684,6.6 18.944742,7.87 17.9227847,8.44 C17.0541209,8.95 16.7475337,10.08 17.2687319,10.94 C17.4322451,11.21 17.6161974,11.44 17.9023455,11.58 C18.2600306,11.77 18.5359591,12.07 18.730131,12.37 C19.1082552,12.99 19.0775965,13.75 18.7096918,14.42 L18.7096918,14.42 L17.9943217,15.62 C17.6161974,16.26 16.9110468,16.66 16.1854571,16.66 C15.827772,16.66 15.4292086,16.56 15.1021823,16.36 C14.8364734,16.19 14.5298861,16.13 14.2028598,16.13 C13.191122,16.13 12.3428973,16.96 12.3122386,17.95 C12.3122386,19.1 11.3720378,20 10.1967868,20 L10.1967868,20 L8.8069248,20 C7.62145424,20 6.68125344,19.1 6.68125344,17.95 C6.6608143,16.96 5.81258967,16.13 4.80085186,16.13 C4.46360592,16.13 4.15701871,16.19 3.90152936,16.36 C3.574503,16.56 3.16572005,16.66 2.81825454,16.66 C2.08244522,16.66 1.37729463,16.26 0.999170395,15.62 L0.999170395,15.62 L0.2940198,14.42 C-0.0841044313,13.77 -0.104543579,12.99 0.273580653,12.37 C0.437093834,12.07 0.743681049,11.77 1.09114656,11.58 C1.37729463,11.44 1.56124696,11.21 1.73497971,10.94 C2.2459584,10.08 1.93937119,8.95 1.07070741,8.44 C0.0589696023,7.87 -0.26805676,6.6 0.314458948,5.61 L0.314458948,5.61 L0.999170395,4.43 C1.59190568,3.44 2.85913283,3.09 3.88109021,3.67 C4.77019314,4.15 5.92500498,3.83 6.44620325,2.98 C6.60971643,2.7 6.70169259,2.4 6.68125344,2.1 C6.6608143,1.71 6.77322961,1.34 6.96740151,1.04 C7.34552574,0.42 8.03023719,0.02 8.77626608,0 L8.77626608,0 Z M9.51207539,7.18 C7.9076023,7.18 6.60971643,8.44 6.60971643,10.01 C6.60971643,11.58 7.9076023,12.83 9.51207539,12.83 C11.1165485,12.83 12.3837756,11.58 12.3837756,10.01 C12.3837756,8.44 11.1165485,7.18 9.51207539,7.18 Z"></path>
        </g>
    </g>
</svg>
        </button>
	</nav>
    <div class="icon-frame">
    <UserIcon height="72px" width="72px"/>
    <p class="name">Danijel Jerinić</p>
</div>
<form action="submit">
    <label for="input">Full Name<span class="mandatory">*</span></label>
    <input type="text" placeholder="Danijel Jerinić">
    <label for="input">Username<span class="mandatory">*</span></label>
    <input type="text" placeholder="LilPasa">
    <label for="input">Email*<span class="mandatory">*</span></label>
    <input type="text" placeholder="jerinicdanijel03@gmail.com">
    <label for="input">Gender<span class="mandatory">*</span></label>
    <input type="text" placeholder="Male">
    <label for="input">Date of Birth<span class="mandatory">*</span></label>
    <input type="text" placeholder="4.8.2003">
    <button class="save-btn">Save changes</button>
</form>
</div>

<style>
    *{
        padding: 0;
        margin: 0;

        box-sizing: border-box;
    }

    .container{
        height: auto;
        width: 100%;

        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 8px;

        padding: 64px 16px 16px 16px;

        overflow: auto;
    }

    h1{
		font-size: 20px;
		font-weight: 500;
		color: #000;
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

    .icon-frame{
        height: max-content;
        width: 100%;

        padding: 40px 0;

        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 16px;

        border-bottom: 1px solid #dcdcdc;
    }

    .name{
        font-size: 20px;
        font-weight: 500;
        color: #000;
    }

    .mandatory{
        color: orangered;
        font-size: 14px;
    }

    form{
        height: max-content;
        width: 100%;

        padding-top: 16px;

        display: flex;
        flex-direction: column;
        gap: 8px;
    }

    input{
        margin-bottom: 16px;
        height: 40px;
        padding-left: 8px;
        border-radius: 5px;

        background-color: #f2f2f2;
        outline: 1px solid #dcdcdc;
        border: none;
    }

    .save-btn{
        height: 40px;
        width: 100%;

        background-color: #000;
        color: #fff;

        border: none;
        outline: none;

        border-radius: 5px;
    }
</style>