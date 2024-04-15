<script lang="ts">
	import { Presentation, Slide, Code } from '@components'
</script>

<Presentation>
	<Slide animate>
		<p class="font-bold text-8xl">Contains Duplicate</p>
	</Slide>

	<Slide animate>
		<p class="font-bold text-3xl mb-8">Contains Duplicate</p>

		<!-- <div data-id="1" class="w-max mx-auto mt-16">[1, 2, 3, 1]</div> -->
		<div class="flex justify-center" data-id="1">
			<div class="flex border border-gray-400 rounded overflow-hidden">
				<!-- Array elements represented as divs -->
				<div class="px-4 py-2 bg-black">1</div>
				<div class="px-4 py-2 bg-black">2</div>
				<div class="px-4 py-2 bg-black">3</div>
				<div class="px-4 py-2 bg-black">1</div>
			</div>
		</div>
	</Slide>

	<Slide animate>
		<!-- <div data-id="1" class="w-max mx-auto mt-16">[1, 2, 3, 1]</div> -->
		<div class="flex justify-center" data-id="1">
			<div class="flex border border-gray-400 rounded overflow-hidden">
				<!-- Array elements represented as divs -->
				<div class="px-4 py-2">1</div>
				<div class="px-4 py-2">2</div>
				<div class="px-4 py-2">3</div>
				<div class="px-4 py-2">1</div>
			</div>
		</div>
	</Slide>
</Presentation>

<style>
	table {
		border-collapse: collapse;
	}
	tr:first-child {
		border: 1px solid #000;
	}
</style>
