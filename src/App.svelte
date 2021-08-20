<script>
	import AboutOne from "./AboutOne.svelte";
	import AboutTwo from "./AboutTwo.svelte";
	import Footer from "./Footer.svelte";
	import HeaderOne from "./HeaderOne.svelte";
	import Navbar from "./Navbar.svelte";
	import OurTeam from "./OurTeam.svelte";
	import Portfolio from "./Portfolio.svelte";
	import Testimoni from "./Testimoni.svelte";
</script>

<div class="poppins bg-[#161616]">
	<Navbar />
	<HeaderOne />
	<AboutOne />
	<AboutTwo />
	<OurTeam />
	<Portfolio />
	<Testimoni />
	<Footer />
</div>

<style global windi:global windi:preflights:global windi:safelist:global>
	.poppins {
		font-family: "Poppins";
	}
</style>
