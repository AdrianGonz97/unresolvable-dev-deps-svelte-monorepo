<script lang="ts">
	import { z } from "zod";

	let { children } = $props();

		let thing = z.object({ foo: z.string() });
	let bar = thing.parse({ foo: "..." });
</script>

<button>
	{bar.foo}
	{@render children?.()}
</button>
