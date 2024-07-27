<script>
	import ContentLayout from '$lib/utils/ContentLayout.svelte';
	import NavBar from '../NavBar/NavBar.svelte';
</script>

<section class="pb-20 h-full bg-[linear-gradient(159deg,#0051FF_0%,#FFFFFF_100%)]">
	<ContentLayout>
		<NavBar />
		<div class="flex md:flex-row flex-col justify-center gap-1 mt-20">
			<div class="max-w-[35rem] rounded-md p-1 w-full max-h-[35rem] border-2 border-black">
				<enhanced:img
					class="w-full h-full rounded-md object-cover"
					src="/static/cats.jpg?w=1024"
					alt="cats "
				/>
			</div>
			<div
				class="max-w-[35rem] md:py-0 py-16 flex border-2 border-black border-b-8 border-r-8 flex-col items-start px-7 justify-center rounded-md p-1 w-full max-h-[35rem] bg-white"
			>
				<h2 class="text-3xl mb-2 font-extrabold">Mister Coby</h2>
				<p>Mr. Coby, The gambling addicted cat.</p>
				<button
					class="uppercase hover:scale-90 duration-200 px-9 mt-8 py-3 text-lg rounded-md text-white bg-black"
					>Buy Now!</button
				>
			</div>
		</div>
		<div
			class="flex max-w-fit px-10 flex-wrap justify-center mt-12 mx-auto bg-white items-center gap-10 gap-y-3 py-2 border-2 rounded-xl border-black border-r-8"
		>
			<p class="sm:text-base text-sm">0x00000000000000000000000</p>
			<button
				class="bg-black scale-110 hover:scale-100 duration-200 hover:bg-white border-black border hover:text-black text-white rounded-full px-5 py-2"
				>Dextools</button
			>
		</div>
	</ContentLayout>
</section>
