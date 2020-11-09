<svelte:options tag="my-child"/>

<style>
    span.green {
        color: green;
        font-size: 5rem;
    }
</style>

<script>
    export let text;
</script>


<span class="green">{text}</span>

