<script>
	import { Search } from 'flowbite-svelte';
  import { Button } from 'flowbite-svelte';
</script>

<form class="flex gap-2 w-full">
  <Search size="md" />
  <Button class="!p-2.5 bg-grey-500">
    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
  </Button>
</form>