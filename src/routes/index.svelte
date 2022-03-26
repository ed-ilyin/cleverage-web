<script>
    import Background from '$lib/Background.svelte'
    import Header from '$lib/Header.svelte'
    import Wrap from '$lib/Wrap.svelte'
    import Bot from '$lib/Bot.svelte'
    import Game from '$lib/Game.svelte'
    import Chats from '$lib/Chats.svelte'
    import Instagram from '$lib/Instagram.svelte'
    import Principles from '$lib/Principles.svelte'
</script>

<Background />
<Header />
<Wrap>
    <Bot />
    <Game />
    <Chats />
    <Instagram />
    <Principles />
</Wrap>

<style>
    :root {
        background-color: #000c;
        color: #fffe;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        text-shadow: 0px 0px 2px #000;
        font-weight: 100;
        text-align: center;
    }
</style>
