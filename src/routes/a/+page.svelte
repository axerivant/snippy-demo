<script lang="ts">
	let snips: Snip[] = [
		{
			content:
				'1 Lorem ipsum dolor sit amet consectetur. Consectetur sed velit urna eget ipsum. Urna nibh mattis pulvinar nisi urna. Tincidunt elementum sed scelerisque nisl. Vestibulum viverra libero malesuada turpis porttitor ultrices.',
			createdOnDate: new Date(),
			isDiscarded: false,
			id: ''
		},
		{
			content:
				'2 Tincidunt elementum sed scelerisque nisl. Vestibulum viverra libero malesuada AS sturpis porttitor ultrices.',
			createdOnDate: new Date(),
			isDiscarded: false,
			id: ''
		},
		{
			content:
				'3 Tincidunt elementum sed scelerisque nisl. Vestibulum viverra libero malesuada turpis porttisssssstor ultrices. Tisncidunt elementum AXER viverra libero malesuada turpis porttitor ultrices.',
			createdOnDate: new Date(),
			isDiscarded: false,
			id: ''
		},
		{
			content:
				'4 Urna nibh mattis pulvinar nisi urna. Tincidunt elementum sed scelerisque nisl. Vestibulum viverra libero malesuada turpis porttitor ultrices.',
			createdOnDate: new Date(),
			isDiscarded: false,
			id: ''
		},
		{
			content: '5 Lorem ipsum dolor sit aitor ultrices.',
			createdOnDate: new Date(),
			isDiscarded: false,
			id: ''
		},
		{
			content:
				'6 Tincidunt elementum sed scelerisque nisl. Vestibulum viverra libero malesuada AS sturpis porttitor ultrices.',
			createdOnDate: new Date(),
			isDiscarded: false,
			id: ''
		},
		{
			content:
				'7 Tincidunt elementum sed scelerisque nisl. Vestibulum viverra libero malesuada turpis porttisssssstor ultrices. Tisncidunt elementum AXER viverra libero malesuada turpis porttitor ultrices.',
			createdOnDate: new Date(),
			isDiscarded: false,
			id: ''
		},
		{
			content:
				'8 Lorem ipsum dolor sit amet consectetur. Consectetur sed velit urna eget ipsum. Urna nibh mattis pulvinar nisi urna. Tincidunt elementum sed scelerisque nisl.',
			createdOnDate: new Date(),
			isDiscarded: false,
			id: ''
		}
	]
</script>

<main class="bg-700 h-screen text-white flex flex-col items-center justify-between p-12">
	<div class="bg-white p-1 w-[50rem] max-h-[50rem] gap-3 columns-2">
		{#each snips as snip}
			<div
				class="bg-[#77FF85] p-3 rounded-sm h-fit mb-3 break-inside-avoid [column-fill_balance]"
			>
				<p class="text-black opacity-90 w-full h-fit">{snip.content}</p>
				<div>
					<div>{snip.createdOnDate.toLocaleDateString()}</div>
				</div>
			</div>
		{/each}
	</div>
	<div>CREATE</div>
</main>
