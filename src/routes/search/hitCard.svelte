<script>

    import { fade } from 'svelte/transition';
    export let hit;
     
</script>
<div class="pb-3">
    <a class="list-none text-xs p-4 bg-white text-gray-500 text-left rounded-md shadow-sm hover:shadow-md flex flex-col " href="/search/{hit.container_id}" transition:fade>
        <p class="uppercase text-xs">{hit.container_id} {hit.order_id} {hit.fulfiller_container_id}</p>
    </a>
</div>


