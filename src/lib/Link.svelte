<script>
    export let href
    export let header = false
</script>

<a {href} class:header target="_blank"><slot /></a>

<style>
    a {
        color: #eefd;
        border-radius: 8px;
        padding: 8px;
    }
    a:hover {
        background-color: #fff2;
    }
    .header {
        margin: 8px;
        font-size: xx-large;
    }
</style>
