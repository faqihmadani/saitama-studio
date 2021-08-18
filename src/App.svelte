<script>
	import AboutOne from "./AboutOne.svelte";
	import AboutTwo from "./AboutTwo.svelte";
	import HeaderOne from "./HeaderOne.svelte";
	import Navbar from "./Navbar.svelte";
	import OurTeam from "./OurTeam.svelte";
</script>

<div class="poppins bg-[#161616]">
	<Navbar />
	<HeaderOne />
	<AboutOne />
	<AboutTwo />
	<OurTeam />
</div>

<style global windi:global windi:preflights:global windi:safelist:global>
	.poppins {
		font-family: "Poppins";
	}

	.roboto {
		font-family: "Roboto";
	}
</style>
