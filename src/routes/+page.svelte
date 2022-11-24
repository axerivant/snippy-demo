<script>
	import { goto } from '$app/navigation'
</script>

<main class="bg-700 h-screen flex flex-col items-center justify-center">
	<div class="w-86 flex flex-col gap-3 mb-24">
		<div class="w-full text-white opacity-80">
			This is the demo version of Snippy. All data is saved to browser local storage. <br /> To
			reset application data, simply hard refresh.
		</div>
		<button on:click={() => goto('/a')} class="bg-500 text-white h-fit w-fit p-3 px-6 rounded">
			start demo
		</button>
	</div>
</main>
