<script>
	import ContentLayout from '$lib/utils/ContentLayout.svelte';

	const NavItem = [
		{ label: 'Chart', link: '#' },
		{ label: 'X', link: '#' },
		{ label: 'Telegram', link: '#' }
	];
</script>

<section class="bg-[linear-gradient(180deg,#0051FF_0%,#6A707C_100%)]">
	<ContentLayout>
		<div class="py-10 flex text-white flex-col items-center">
			<h2 class="uppercase text-4xl font-bold">MISTER MIGGLES</h2>
			<ul class="flex gap-5 mt-2">
				{#each NavItem as item}
					<li class="uppercase font-medium">{item.label}</li>
				{/each}
			</ul>
			<div>
				<button
					class="uppercase text-black mt-5 font-medium border-b-4 border-r-4 scale-110 hover:scale-100 duration-300 border-black px-5 py-1 rounded-full hover:bg-gray-500 hover:text-white bg-slate-100"
					>buy now</button
				>
			</div>
		</div>
	</ContentLayout>
</section>
