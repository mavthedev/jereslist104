<script lang="ts">
	import { getUser } from "@lucia-auth/sveltekit/client";

	const user = getUser();
</script>

{JSON.stringify($user)}