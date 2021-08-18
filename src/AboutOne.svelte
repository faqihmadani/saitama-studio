<script>
	import PrimaryButton from "./PrimaryButton.svelte";
</script>

<section class="poppins bg-[#161616] text-white body-font pt-10 md:pt-16">
	<div
		class="mx-auto container grid gap-x-8 gap-y-7 md:grid-cols-2 xl:grid-rows-4 transform scale-90 md:scale-100"
	>
		<h1
			class="text-white text-[30px]  sm:text-[35px] md:text-[42px] lg:text-[54px] font-bold roboto leading-snug md:leading-snug lg:leading-snug"
		>
			Build Your Digital Product With Us
		</h1>
		<div class=" row-span-3 md:row-span-4 scale-90 md:scale-100">
			<img src="about1.png" alt="about1" />
		</div>
		<div class=" row-span-3 md:row-span-4">
			<img src="about2.png" alt="about2" />
		</div>
		<div>
			<p
				class="text-white col-span-3 leading-normal sm:leading-loose text-[20px] mb-8 md:mb-5"
			>
				We are a team full of people who are highly skilled in the fields of UI
				/ UX, Web development and SEO. Over the years we have been doing
				strategic planning, creative
			</p>
			<PrimaryButton>Explore Now</PrimaryButton>
		</div>
	</div>
</section>

<style global windi:global windi:preflights:global windi:safelist:global>
</style>
