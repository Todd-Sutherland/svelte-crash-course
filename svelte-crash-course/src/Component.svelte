<h1>Another Component</h1>

<p>Bye {name}</p>

<div>
    <a href="https://google.com">Link to google</a>
</div>

<style>
    h1 {
        animation: zoom 5s infinite; 
        /* this will not work here because zoom is not defined in Component.svelte */
    }
</style>

<script>
    let name = 'Todd'
</script>