<script>
    import "../app.scss";
</script>

<main>
    <slot />
</main>

<style lang="scss">
    :global(body) {
        @apply bg-white dark:bg-black text-black dark:text-white;
    }
</style>
