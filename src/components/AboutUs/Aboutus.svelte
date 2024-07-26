<script>
	import ContentLayout from '$lib/utils/ContentLayout.svelte';
</script>

<ContentLayout>
	<div
		class=" py-20 border-2 border-r-8 border-b-8 text-white border-black mt-32 mb-10 rounded-lg bg-[linear-gradient(-159deg,#0051FF_0%,#6A707C_110%)]"
	>
		<div class="flex px-2 md:gap-10 gap-2 flex-col items-center">
			<div class="max-h-[30rem] max-w-[30rem]">
				<enhanced:img class=" object-cover" src="/static/cats2.jpg?w=1024" alt="cat" />
			</div>
			<div class="max-h-[30rem] max-w-[30rem]">
				<enhanced:img class=" object-cover" src="/static/cats3.jpg?w=1024" alt="cat" />
			</div>
		</div>
		<div class="max-w-fit text-center mx-auto mt-10">
			<h3 class="mb-2 text-4xl font-bold">What Is $MIGGLES?</h3>
			<p class="font-medium">Mr. Coby, The gambling addicted cat.</p>
			<button
				class="uppercase text-black mt-7 font-medium border-b-4 border-r-4 scale-110 hover:scale-100 duration-300 border-black px-5 py-2 rounded-full hover:bg-black hover:text-white bg-white"
				>How was Mr. Coby Born</button
			>
		</div>
	</div>
</ContentLayout>
