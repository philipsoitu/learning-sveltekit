<script>
    let name="yo";

    function addToName(){
        name = name + "yo";
    }
</script>

<h1>Welcome to SvelteKit</h1>
<p>{name}</p>
<button on:click={addToName}>
    Add to name
</button>
