<script>
    //import Navegacion from './navegacion1.svelte'

    import Navegacion from '$lib/components/Nav.svelte'
    import './app.css'
</script>

<main>
    <Navegacion/>
    <slot></slot>

</main>