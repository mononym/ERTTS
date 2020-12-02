<script lang="ts">
  import Tailwindcss from "./Tailwind.svelte"
  import Router from "@roxi/routify/runtime/Router.svelte";
  import { routes } from "../.routify/routes";

</script>

<Router {routes} config={{ useHash: true }} />
<Tailwindcss />
