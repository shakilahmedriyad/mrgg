<script>
	import ContentLayout from '$lib/utils/ContentLayout.svelte';
</script>

<ContentLayout>
	<div
		class="  pt-20 border-2 flex flex-col items-center text-white border-black mb-10 rounded-lg bg-[linear-gradient(-159deg,#0051FF_0%,#6A707C_110%)]"
	>
		<div class="max-w-fit text-center mx-auto mb-10">
			<h3 class="mb-2 text-4xl font-bold">Why $Sunko?</h3>
			<p class="text-xl">
				$Sunko is all about the commmunity, everything is designed to encourage our people to
				actively contribute to the token's growth
			</p>
		</div>
		<div class="flex px-2 gap-2 flex-col items-center">
			<div class="max-h-[30rem] max-w-[30rem]">
				<enhanced:img class=" object-cover" src="/static/cats2.png?w=1024" alt="cat" />
			</div>
			<div class="max-w-fit mt- text-center mx-auto mb-10">
				<p class="mb-2 text-4xl px-2 font-bold sm:px-16">$Sunko the first Unique cat on TRX</p>
				<p class="text-xl">
					Successful meme coins share a common thread a community that believes in our potential and
					collaborates to grow together <br /> <br /> Are you ready to join $Sunko on this journey?
				</p>
			</div>
			<div class="max-h-[50rem] max-w-[80rem]">
				<enhanced:img class=" object-cover" src="/static/sunko.png?w=1024" alt="cat" />
			</div>
		</div>
	</div>
</ContentLayout>
