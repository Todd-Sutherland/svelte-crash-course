<script>
    let count = 0;

    function increment() {
        count ++;
    }
</script>

{count}

<button on:click={increment}>Click Me</button>