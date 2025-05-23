<script lang="ts">
	import { foo } from "@workspace/ui/components/button/index.js";

	const parsed = foo.parse({ bar: "baz" });
</script>

Look Pa, it's zod! {parsed}
