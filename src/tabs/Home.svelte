<script>
	import UserBar from '../components/UserBar.svelte';
	import SearchBar from '../components/SearchBar.svelte';
	import CategoryToggle from '../components/CategoryToggle.svelte';
	import Suggested from '../components/Suggested.svelte';
	import TabToggler from '../components/TabToggler.svelte';
	import LocationSuggestion from '../components/LocationSuggestion.svelte';
</script>

<div class="container">
	<UserBar />
	<div class="ad"></div>
	<SearchBar />
	<CategoryToggle />
	<Suggested />
	<LocationSuggestion/>
	<Suggested />

	<TabToggler />
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

		padding: 16px;

		background-color: #fff;

		display: flex;
		flex-direction: column;

		gap: 24px;

		padding-bottom: 65px;
	}

	.ad {
		height: 120px;
		width: 100%;

		background-image: url("cover-test3.jpg");
		background-position: center;
		background-repeat: no-repeat;
		background-size: cover;

		border-radius: 10px;

		background-color: #252525;
	}
</style>
