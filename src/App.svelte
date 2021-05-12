<script>
	import Router from 'svelte-spa-router'
	import routes from './routes'
    import {link} from 'svelte-spa-router'
</script>
<div>
	<a href="/" use:link>Home</a>
</div>
<Router {routes} />

<style>

</style>