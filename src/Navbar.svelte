<script>
	import { fade } from "svelte/transition";

	let isNavOpen = false;

	const handleNav = () => {
		isNavOpen = !isNavOpen;
	};
</script>

<header class="text-gray-600 bg-[#2E2E2E] body-font fixed w-full z-50">
	<div class="container mx-auto flex p-5 flex-row justify-between items-center">
		<a href="/" class="flex title-font font-medium  text-gray-900 ">
			<img src="favicon.svg" alt="logo" />
			<span class="ml-3 text-xl text-white font-bold">Saitama Studio</span>
		</a>
		<div class="md:hidden fill-current text-white" on:click={handleNav}>
			<svg
				xmlns="http://www.w3.org/2000/svg"
				class="h-6 w-6"
				fill="none"
				viewBox="0 0 24 24"
				stroke="currentColor"
			>
				<path
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					d="M4 6h16M4 12h16M4 18h16"
				/>
			</svg>
		</div>
		<nav
			class="hidden md:ml-auto md:flex flex-wrap items-center text-base justify-center"
		>
			<a href="/" class="mr-5 poppins font-medium text-white hover:underline"
				>About</a
			>
			<a href="/" class="mr-5 poppins font-medium text-white hover:underline"
				>Portfolio</a
			>
			<a href="/" class="mr-5 poppins font-medium text-white hover:underline"
				>Blog</a
			>
			<a href="/" class="mr-5 poppins font-medium text-white hover:underline"
				>Contact</a
			>
		</nav>
		{#if isNavOpen}
			<nav
				transition:fade={{ duration: 200 }}
				class={isNavOpen
					? "block bg-[#2E2E2E] top-0 left-0 absolute w-screen h-screen md:hidden md:ml-auto flex flex-col items-center text-base justify-center space-y-3"
					: "hidden"}
			>
				<div
					class="absolute top-6 right-5 fill-current text-white"
					on:click={handleNav}
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-6 w-6"
						fill="none"
						viewBox="0 0 24 24"
						stroke="currentColor"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M6 18L18 6M6 6l12 12"
						/>
					</svg>
				</div>
				<a
					href="/"
					class="p-1 mr-5 poppins font-medium text-white hover:underline"
					>About</a
				>
				<a
					href="/"
					class="p-1 mr-5 poppins font-medium text-white hover:underline"
					>Portfolio</a
				>
				<a
					href="/"
					class="p-1 mr-5 poppins font-medium text-white hover:underline"
					>Blog</a
				>
				<a
					href="/"
					class="p-1 mr-5 poppins font-medium text-white hover:underline"
					>Contact</a
				>
			</nav>
		{/if}
	</div>
</header>

<style global windi:global windi:preflights:global windi:safelist:global>
</style>
