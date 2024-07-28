<script>
	const NavItem = [
		{ label: 'Chart', link: '#' },
		{ label: 'X', link: 'https://x.com/thecatcoby' },
		{ label: 'Telegram', link: 'https://t.me/CatCoby' }
	];
</script>

<nav class="flex px-4 justify-between py-10 items-center">
	<div class="shrink-1"></div>
	<ul class=" md:flex hidden text-white gap-5 font-medium">
		{#each NavItem as item}
			<a target="_blank" href={item.link}
				><li class="uppercase cursor-pointer hover:text-gray-200 text-lg">{item.label}</li></a
			>
		{/each}
	</ul>
	<button
		class="uppercase font-medium border-b-4 border-r-4 scale-110 hover:scale-100 duration-300 border-black px-5 py-1 rounded-full hover:bg-gray-500 hover:text-white bg-slate-100"
		>buy now</button
	>
</nav>
