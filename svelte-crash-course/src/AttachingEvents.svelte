<script>
    function onClick(event){
        console.log('clicked')
    }

    function clickModifier(event){
        event.preventDefault() // to prevent the default behavior of the submit, so you can make some validation and cancel the request,etc.
        console.log('good job')
    }
//vanilla JS method- h1.addEventListener('click', onClick)
</script>

<h1 on:click={onClick}>Event Listeners</h1>

<!-- Or we can define an anonymous arrow function inline to the on:click -->
<h1 on:click={() => {console.log('clicked again')} }>Event Listeners</h1>

<!-- Event modifiers -->
<h1 on:click={clickModifier}>Event Modifier</h1>

<!-- You can also add the event modifier inline -->
<h1 on:click|preventDefault={() => console.log('hello')}>Event Modifier Again</h1>