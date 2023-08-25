<script lang="ts">
    export let name: string;
</script>

<main>
    <h1>work in progress :3</h1>
    <img
        src="images/A_BlobCat_PeekWave.gif"
        alt="A blob cat gif where blob cat peaks from behind a brick wall waving"
    />
</main>

<style>
    main {
        text-align: center;
        padding: 1em;
        max-width: 240px;
        margin: 0 auto;
    }

    h1 {
        color: var(--text);
        text-transform: lowercase;
        font-size: 6em;
        font-weight: bold;
    }

    .large {
        font-size: 3em;
    }

    @media (min-width: 640px) {
        main {
            max-width: none;
        }
    }
</style>

