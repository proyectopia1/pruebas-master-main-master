
<nav class="nav-links">
    <a href="/.." ><img class="logo" src={logo} alt="Logo de Svelte" width="100" ></a>
        <a href="/media_tecnicas/md_sw">Software</a>
        <a href="/media_tecnicas/md_dg">Diseño</a>
        <a href="/media_tecnicas/md_dp">Deporte</a>
        <a href="/media_tecnicas/md_cc">Comercio</a>
        <a href="/registro" data-sveltekit-preload-data="tap">Admin</a>
    
</nav>

<script>
    import logo from '$lib/assents/logo.png';
  </script>

<style>
    .logo{
        margin-left: -100px;
        margin-right: 100px;
        height: 150px;
        width: 150px;

    }
    nav {
        background-color: #171717;
        padding: 3rem;
    }

    .nav-links {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 5rem;
    }

    a {
        color: #fff;
        text-decoration: none;
        font-size: 1.5rem;
    }

    a:hover {
        color: #007bff;
    }
</style>