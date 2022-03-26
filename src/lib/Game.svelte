<script>
    import Box from '$lib/Box.svelte'
</script>

<Box>
    Как играть?
    <Box>Аудио</Box>
    <iframe
        src="https://www.youtube.com/embed/mtriR-H3IKc"
        title="Cleveragebot"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen />
    <Box>Текст https://telegra.ph/Obshchie-pravila-03-30</Box>
</Box>

<style>
    iframe {
        border-radius: 8px;
    }
</style>
