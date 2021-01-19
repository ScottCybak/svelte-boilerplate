<script lang="ts">
	
	import { Router, Route } from 'svelte-routing';
	import Home from './components/Home.svelte';

	let url = '';
</script>

<router-outlet>
	<Router url={url}>
		<Route component={Home}></Route>
	</Router>
</router-outlet>
