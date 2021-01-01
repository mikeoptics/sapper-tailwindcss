<script>
	import Nav from '../components/Nav.svelte';
	import GlobalStyle from "../components/GlobalStyle.svelte";

	export let segment;
</script>

<style>
main {
	@apply p-3;
}
</style>

<Nav {segment}/>

<main>
	<GlobalStyle />
	<slot></slot>
</main>
