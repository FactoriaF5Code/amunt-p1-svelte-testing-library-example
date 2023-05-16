<script>
    export let word;

    $: initial = word.at(0);
    $: size = word.length;
</script>

<div class="card">
    <h1>"{word}"</h1>
    <p>tiene {size} letras</p>
    <p>comienza por la letra {initial}</p>
</div>

<style>
    div {
        border: 1px dashed orangered;
    }
</style>
