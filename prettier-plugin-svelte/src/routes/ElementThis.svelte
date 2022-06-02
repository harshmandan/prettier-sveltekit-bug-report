<script>
export let href = ''
</script>

<svelte:element this="{href ? 'a' : 'button'}" href="{href}"></svelte:element>
