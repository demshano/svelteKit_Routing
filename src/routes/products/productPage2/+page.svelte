<script>
    import Header from "$lib/components/Header.svelte"
</script>

<Header />

<div class="flex flex-col justify-center items-center mt-[200px]">
    <h1 class="text-3xl">Welcome to the Product Page 2</h1>
    <p class="text-lg text-center">This is a simple Contact page.</p>
</div>

<div class="flex justify-center gap-4 mt-[100px]">
    <a
        class="bg-slate-200 py-4 px-8 rounded-sm font-semibold"
        href="/products/productPage1">product page one</a
    >
    <a
        class="bg-slate-200 py-4 px-8 rounded-sm font-semibold"
        href="/products/productPage2">product page two</a
    >
</div>