<script>
    import Foo from './Foo.svelte';
</script>

<Foo foo="">
    {#snippet snippetOne()}
    {/snippet}
    <div></div>
    {#snippet snippetTwo()}
    {/snippet}
</Foo>
