<script lang="ts">
	import { getFoo } from '@repo/core';
	import { MyCounterButton } from '@repo/ui';
</script>

<h1>Web</h1>
<MyCounterButton />
<p>Visit {getFoo()}<a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
