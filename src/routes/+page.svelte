<script lang="ts">
	import hero from '/src/illustration-hero.svg';
	import music from '/src/icon-music.svg'
</script>

<div class="grid min-h-screen place-items-center bg-[#d4ccff]">
	<div>
		<div class="grid place-items-center w-1/2 rounded-t-2xl">
			<img class="rounded-t-2xl" src={hero} alt="">
		</div>
		<div class="grid place-items-center w-1/2 rounded-b-2xl bg-white">
			<h1 class="font-bold text-2xl mt-10">Order Summary</h1>
			<p class="grid place-items-center my-5 mx-10 font-light text-center">You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!</p>
			<div class="flex content-center bg-[#d4ccff]/70 w-3/4 h-20 mb-5 rounded-2xl">
				<div class="flex my-4">
					<img  class="ml-5 mr-2" src={music} alt="">
					<p class="text-sm"><b>Annual Plan</b><br/>$59.99/year</p>
					<button class="ml-10">Change</button>
				</div>
			</div>
		</div>
	</div>
</div>

<style lang="postcss">
</style>
