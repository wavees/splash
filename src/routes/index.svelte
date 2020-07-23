<script>
  // Importing modules.
  import { goto } from "@sapper/app";
  import { onMount } from "svelte";

  // Let's just redirect our user to
  // /hosting/portals 
  onMount(() => {
    goto("/hosting/portals");
  });
</script>