<script lang="ts">
	import { BrokenButton } from "broken";
	import { WorkingButton } from "working";
</script>

<!-- uncomment this and the import to break -->
<BrokenButton>Transitive Svelte Dev Dep</BrokenButton>

<WorkingButton>Transitive JS only Dep is Working</WorkingButton>
