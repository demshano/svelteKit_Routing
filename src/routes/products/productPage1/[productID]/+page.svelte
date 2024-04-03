<script>
    import { page } from '$app/stores';
    const productID = $page.params.productID;
</script>

<div class="bg-gray-200 w-[100px] p-4">
    <p>this is dynamic routing</p>
    <p>product-id: {productID}</p>
</div>

