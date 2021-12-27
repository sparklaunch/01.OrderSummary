<script lang="ts">
    import Card from "./components/Card.svelte";
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
        href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap"
        rel="stylesheet"
    />
</svelte:head>

<main>
    <Card />
</main>

<style>
    main {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: url("/assets/pattern-background-desktop.svg")
            rgb(220, 229, 253);
        background-repeat: no-repeat;
        background-size: contain;
    }
    @media screen and (max-width: 1440px) {
        main {
            background: url("/assets/pattern-background-mobile.svg")
                rgb(220, 229, 253);
            background-repeat: no-repeat;
            background-size: cover;
            position: static;
            padding: 50px 0;
            height: auto;
        }
    }
</style>
