<script lang="ts">
	import SomeIcon from "@lucide/svelte/icons/bubbles";

	let { children } = $props();
</script>

<button>
	<SomeIcon />
	{@render children?.()}
</button>
