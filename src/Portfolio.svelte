<script>
	import PrimaryButton from "./PrimaryButton.svelte";
</script>

<section
	class="poppins bg-[#161616] text-white body-font pt-10 md:pt-16 mt-5 md:mt-14 transform scale-90 md:scale-100"
>
	<div
		class="container mx-auto grid grid-cols-1 md:grid-cols-2 gap-y-10 md:gap-y-14 gap-x-16"
	>
		<div class="md:col-span-2 md:flex justify-between items-center">
			<div class="md:w-[50%]  lg:w-[40%]">
				<h1
					class="text-white text-[30px]  sm:text-[35px] md:text-[42px] lg:text-[54px] font-bold roboto leading-snug md:leading-snug lg:leading-snug"
				>
					See Our Works
				</h1>
				<p
					class="text-white col-span-2 leading-normal sm:leading-loose text-[20px] mt-8 md:mb-0"
				>
					Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
					sint.
				</p>
			</div>
			<div class="hidden md:block">
				<PrimaryButton>More Project</PrimaryButton>
			</div>
		</div>
		<div class="flex flex-col justify-center space-y-5  md:space-y-8 md:hidden">
			<div>
				<h1
					class="text-white text-[30px]  sm:text-[35px] md:text-[42px] lg:text-[54px] font-bold roboto leading-snug md:leading-snug lg:leading-snug"
				>
					Dolanan - Travel
				</h1>
				<h1
					class="text-white text-[30px]  sm:text-[35px] md:text-[42px] lg:text-[54px] font-bold roboto leading-snug md:leading-snug lg:leading-snug"
				>
					Landing Page
				</h1>
			</div>
			<p
				class="text-white col-span-2 leading-normal sm:leading-loose text-[20px] mt-8"
			>
				Dolanan is a landing page for travelers looking for the best vacation
				spots in the world
			</p>
			<div class="hidden md:block">
				<PrimaryButton>Explore Now</PrimaryButton>
			</div>
		</div>
		<img src="page1.png" alt="page1" />
		<div class="md:hidden block">
			<PrimaryButton>Explore Now</PrimaryButton>
		</div>
		<div class="md:flex flex-col justify-center  space-y-8 hidden">
			<div>
				<h1
					class="text-white text-[30px]  sm:text-[35px] md:text-[42px] lg:text-[54px] font-bold roboto leading-snug md:leading-snug lg:leading-snug"
				>
					Dolanan - Travel
				</h1>
				<h1
					class="text-white text-[30px]  sm:text-[35px] md:text-[42px] lg:text-[54px] font-bold roboto leading-snug md:leading-snug lg:leading-snug"
				>
					Landing Page
				</h1>
			</div>
			<p
				class="text-white col-span-2 leading-normal sm:leading-loose text-[20px] mt-8"
			>
				Dolanan is a landing page for travelers looking for the best vacation
				spots in the world
			</p>
			<PrimaryButton>Explore Now</PrimaryButton>
		</div>

		<!-- Portfolio 2 -->
		<div class="flex flex-col justify-center space-y-5  md:space-y-8">
			<div>
				<h1
					class="text-white text-[30px]  sm:text-[35px] md:text-[42px] lg:text-[54px] font-bold roboto leading-snug md:leading-snug lg:leading-snug mt-16 md:mt-0"
				>
					RecehTok - SaaS
				</h1>
				<h1
					class="text-white text-[30px]  sm:text-[35px] md:text-[42px] lg:text-[54px] font-bold roboto leading-snug md:leading-snug lg:leading-snug"
				>
					Landing Page
				</h1>
			</div>
			<p
				class="text-white col-span-2 leading-normal sm:leading-loose text-[20px] mt-8"
			>
				Receh Tok is a SaaS landing page that aims to make Crypto trading easier
			</p>
			<div class="hidden md:block">
				<PrimaryButton>Explore Now</PrimaryButton>
			</div>
		</div>
		<img src="page2.png" alt="page2" />
		<div class="md:hidden block">
			<PrimaryButton>Explore Now</PrimaryButton>
		</div>
		<div class="md:hidden block">
			<PrimaryButton>More Project</PrimaryButton>
		</div>
	</div>
</section>

<style global windi:global windi:preflights:global windi:safelist:global>
</style>
