<script>
	import SwiperCore, { Navigation, Pagination, Scrollbar, A11y } from "swiper";

	// Import Swiper Svelte components
	import { Swiper, SwiperSlide } from "swiper/svelte";

	// Import Swiper styles
	import "swiper/swiper-bundle.min.css";

	// install Swiper modules
	SwiperCore.use([Navigation, Pagination, Scrollbar, A11y]);
</script>

<section
	class="poppins bg-[#161616] text-white body-font pt-10 md:pt-16 mt-5 transform scale-75 md:scale-100 "
>
	<div
		class="md:grid grid-cols-3 gap-10 container mx-auto md:mt-20 overflow-x-hidden"
	>
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
		</div>
		<Swiper
			spaceBetween={10}
			slidesPerView={1}
			loop
			centeredSlides
			centeredSlidesBounds
		>
			<SwiperSlide>
				<img src="tim1.png" alt="tim1" />
			</SwiperSlide>
			<SwiperSlide>
				<img src="tim2.png" alt="tim2" />
			</SwiperSlide>
			<SwiperSlide>
				<img src="tim3.png" alt="tim3" />
			</SwiperSlide>
		</Swiper>
	</div>
</section>

<style global windi:global windi:preflights:global windi:safelist:global>
</style>
