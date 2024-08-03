<script>
	import ContentLayout from '$lib/utils/ContentLayout.svelte';
</script>

<ContentLayout>
	<div
		class="  py-20 border-2 border-r-8 flex flex-col items-center border-b-8 text-white border-black mb-10 rounded-lg bg-[linear-gradient(-159deg,#0051FF_0%,#6A707C_110%)]"
	>
		<div class="max-w-fit text-center mx-auto mb-10">
			<h3 class="mb-2 text-4xl font-bold">Why $Coby ?</h3>
			<p class="text-xl">
				$Coby is all about the commmunity, everything is designed to encourage our people to
				actively contribute to the token's growth
			</p>
		</div>
		<div class="flex px-2 md:gap-10 gap-2 flex-col items-center">
			<div class="max-h-[30rem] max-w-[30rem]">
				<enhanced:img class=" object-cover" src="/static/cats2.jpg?w=1024" alt="cat" />
			</div>
			<div class="max-w-fit mt-10 text-center mx-auto mb-10">
				<p class="text-xl px-2 sm:px-16">
					Successful meme coins share a common thread a community that believes in our potential and
					collaborates to grow together <br /><br /> Are you ready to join $Coby on this journey?
				</p>
			</div>
			<div class="max-h-[30rem] max-w-[30rem]">
				<enhanced:img class=" object-cover" src="/static/cats3.jpg?w=1024" alt="cat" />
			</div>
		</div>
	</div>
</ContentLayout>
