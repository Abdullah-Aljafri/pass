<script>
	import { SliceZone } from '@prismicio/svelte';

	import { components } from '$lib/slices/index.js';

	export let data;
</script>

<SliceZone slices={data.slices} {components} />
