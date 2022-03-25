<script>
	import Header from '$lib/Header.svelte';
	import Wrap from '$lib/Wrap.svelte';
	import Bot from '$lib/Bot.svelte';
	import Game from '$lib/Game.svelte';
	import Chats from '$lib/Chats.svelte';
	import Instagram from '$lib/Instagram.svelte';
</script>

<Header />
<Wrap>
	<Bot />
	<Game />
	<Chats />
	<Instagram />
</Wrap>

<style>
	:root {
		background-color: #000b;
		color: #fffe;
	}
</style>
