<script>
    import Foo from './Foo.svelte';
</script>

<Foo >
    {#snippet snippetOne()}
    {/snippet}
    <div></div>
    {#snippet snippetTwo()}
    {/snippet}
</Foo>
