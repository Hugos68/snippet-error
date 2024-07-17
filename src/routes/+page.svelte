<script>
    import Foo from './Foo.svelte';
</script>

<Foo foo="">
    {#snippet snippetOne()}
    {/snippet}
    <label>Test</label>
    {#snippet snippetTwo()}
    {/snippet}
</Foo>
