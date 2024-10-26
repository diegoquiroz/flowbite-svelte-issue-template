<script>
  import { Heading, P, List, Li, Label, MultiSelect, Datepicker } from 'flowbite-svelte';

  let twentysix = new Date("2024-10-26T19:47:48.000Z");
</script>

<div class='p-9'>
<Heading tag="h1">Flowbite-Svelte Playground</Heading>
<List tag="ol">
  <Li class="text-2xl">Fork this Stackblitz project</Li>
  <Li class="text-2xl">Update Flowbite-Svelte by running `pnpm i -D flowbite-svelte@latest`</Li>
  <Li class="text-2xl">Run `pnpm update` to update dependencies.</Li>
  <Li class="text-2xl">Add your code</Li>
</List>

<Datepicker value={twentysix} />

</div>

