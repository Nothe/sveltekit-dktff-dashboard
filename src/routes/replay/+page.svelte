<script>
  import { Listgroup } from 'flowbite-svelte'
	import ProgressBar from './ProgressBar.svelte';
  let links = [
   { name: "e1eea9c9-4b7a-40c8-ad44-61c35ce8ef0d", href: "/accordions", progress:"23" },
   { name: "7660367a-b85a-47a1-a9f1-09603b0863e7", href: "/alerts" , progress:"65" },
   { name: "d77d10d2-2521-47bd-88b5-76405d83e2c9", href: "/badges" , progress:"75"  },
   { name: "15435dff-56cb-4024-ad32-6e5e7c1487c2", href: "/breadcrumbs", progress:"92"  },
  ];


</script>

<h1 class="pt-12 pb-12">Replay</h1>

<div  class="ml-5">

  <Listgroup active items={links} let:item class="w-auto">
  {item.name}
  <div class="pl-12">
  <ProgressBar />

  </div>
  
  </Listgroup>

</div>
  