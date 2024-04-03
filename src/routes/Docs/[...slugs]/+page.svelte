<script>
    import { page } from "$app/stores";

    console.log($page.params.slugs);
    const slugArray = $page.params.slugs.split("/");
</script>

{#if slugArray.length === 1}
    <h1>viewing docs feature {slugArray[0]}</h1>
{:else if slugArray.length === 2}
    <h1>viewing docs feature chapters {slugArray[1]}</h1>
{/if}
