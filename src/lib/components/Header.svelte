<!-- Header.svelte -->

<div
    class="w-full bg-gray-200 rounded-lg h-12 shadow-md flex justify-end items-center gap-4 px-4 md:px-8"
>
    <p class="mr-[640px] font-semibold text-2xl tracking-widest">
        SvelteKit Routing
    </p>

    <a href="/" class="nav-link">Home</a>
    <a href="/about" class="nav-link">About</a>
    <a href="/products" class="nav-link">Products</a>
    <a href="/contact" class="nav-link">Contact</a>
</div>

<style>
    .nav-link {
        padding: 0.5rem 1rem;
        border-radius: 0.375rem;
        color: #4b5563;
        transition: background-color 0.3s ease;
    }

    .nav-link:hover {
        background-color: #cbd5e0;
    }
</style>
