<script>
    import Foo from './Foo.svelte';
</script>

<Foo >
    {#snippet foo()}{/snippet}
    <div></div>
    {#snippet bar()}{/snippet}
</Foo>
