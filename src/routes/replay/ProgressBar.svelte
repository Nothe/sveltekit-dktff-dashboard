<script>
	import { Progressbar } from 'flowbite-svelte';

  function getRandomNumber() {
  return Math.floor(Math.random() * (95 - 10 + 1) + 10);
}

  let progress = getRandomNumber();
</script>

<div class="w-full">
  <Progressbar progress = {progress} size="h-4" labelInside />
</div>