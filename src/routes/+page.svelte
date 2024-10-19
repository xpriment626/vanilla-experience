<script>
    let startNum = 1;
</script>

<section class="flex flex-col justify-center items-center h-screen">
    <h1 class="text-blue-200 font-bold">Welcome to SvelteKit</h1>
    <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
    <h3>{startNum}</h3>
    <button on:click={() => startNum = startNum * 2} class="bg-blue-200 px-4 py-2 mt-2 rounded">Double Me!</button>
    <button on:click={() => startNum = 1} class="bg-blue-200 px-4 py-2 mt-2 rounded">Reset</button>
</section>
