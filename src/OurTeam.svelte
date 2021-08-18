<script>
	import { onMount } from "svelte";
	import "swiper/swiper-bundle.min.css";
	import Swiper, { Navigation } from "swiper";

	Swiper.use([Navigation]);

	onMount(() => {
		const swiper = new Swiper(".swiper-container", {
			navigation: {
				nextEl: ".swiper-button-next",
				prevEl: ".swiper-button-prev",
			},
		});
	});
</script>

<section
	class="poppins bg-[#161616] text-white body-font pt-10 md:pt-16 mt-5 md:mt-14"
>
	<div class="md:grid grid-cols-3 container mx-auto swiper-container">
		<div>
			<h1
				class="text-white text-[30px]  sm:text-[35px] md:text-[42px] lg:text-[54px] font-bold roboto leading-snug md:leading-snug lg:leading-snug"
			>
				Meet Our Awesome Team
			</h1>
			<p
				class="text-white col-span-2 leading-normal sm:leading-loose text-[20px] mb-8 md:mb-5"
			>
				Let's get acquainted with the great people behind Saitama Studio so that
				we can get closer to you
			</p>
			<div>
				<img class="swiper-button-prev" src="left-button.svg" alt="previous" />
				<img class="swiper-button-next" src="right-button.svg" alt="next" />
			</div>
		</div>
		<div class="swiper-wrapper col-span-2">
			<!-- Slides -->
			<div class="swiper-slide">Slide 1</div>
			<div class="swiper-slide">Slide 2</div>
			<div class="swiper-slide">Slide 3</div>
		</div>
	</div>
</section>

<style global windi:global windi:preflights:global windi:safelist:global>
</style>
