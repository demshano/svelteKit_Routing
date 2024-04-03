<script>
    import Header from "../lib/components/Header.svelte";
</script>

<slot />

<Header />

<div class="flex flex-col justify-center items-center mt-[200px]">
    <h1 class="text-3xl">Welcome to the Home Page</h1>
    <p class="text-lg text-center">This is a simple home page.</p>
</div>


