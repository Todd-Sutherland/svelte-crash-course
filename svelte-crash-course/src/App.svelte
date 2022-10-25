<!-- <h1>My first svelte component</h1> -->

<!-- <p>Hello {name}</p> -->

<!-- <div class="links">
    <a href="https://google.com">Google</a>
</div> -->

<!-- <Component /> -->
<!-- <AddingData/> -->
<Reactivity />

<!-- Only the elements within App.svelte will be affected by these style attributes -->
<!-- When you add styles to elements, svelte will automatically add a special svelte class to those elements -->
<style>
    /* h1 {
        color: rebeccapurple;
        animation: zoom 5s infinite;
    }

    p {
        font-size: 44px;
    }

    .links {
        text-align: right;
    }
    @keyframes zoom {
        0%, 100% {transform: scale(3)}
        50% {transform: scale(0.5);}
    } */
</style>

<script>
    let name = 'Todd'
    import Component from './Component.svelte'
    import AddingData from './AddingData.svelte';
    import Reactivity from './Reactivity.svelte';
</script>