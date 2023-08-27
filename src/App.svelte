<script lang="ts">
    export let title: string;
</script>

<main>
    <h1>{title}</h1>
    <img
        src="images/A_BlobCat_PeekWave.gif"
        alt="A blob cat gif where blob cat peaks from behind a brick wall waving"
    />

    <h2>services</h2>

    <ul role="list">
        <li>
            <a href="https://keys.lotta.gay">keyserver</a>
            <p>
            this doesn't quite work yet and i need to set up a
            <br />
            mail server and ldap for the confirmation mails
            </p>
        </li>
    </ul>

    <h2>links to me elsewhere</h2>
    <ul role="list">
        <li class="">
            <a href="https://blahaj.zone/@cherry">fedi</a>
        </li>
        <li>
            <a href="https://github.com/git-girl">github</a>
        </li>
    </ul>
</main>

<style global lang="postcss">
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

    @layer components {
        h1 {
            @apply m-24;
            @apply text-6xl;
            @apply lg:text-8xl;
        }

        h2 {
            @apply text-4xl;
            @apply m-12;
        }

        h3 {
            @apply text-2xl;
            @apply m-6;
        }

        ul {
            @apply list-disc;
            @apply list-inside;
        }

        html, body {
            @apply text-center;
            @apply text-text;
            @apply bg-base;
            @apply h-full;
            @apply w-full; 
            @apply font-sans; 
            @apply font-normal;
            @apply hyphens-auto;
        }

        img {
            @apply mx-auto;
        }

        main {
            @apply h-full;
            @apply my-auto;
        }

        a {
            @apply text-sapphire;
            @apply font-bold;
            @apply decoration-2;
            @apply hover:underline;
            @apply focus:underline;
            @apply visited:text-mauve;
        }
    }
</style>
