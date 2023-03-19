<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
	import Formulario from './Formulario.svelte';
</script>

<svelte:head>
	<title>Formulario de Participación ciudadana y compromisos de la Defensoría del Pueblo de Colombia</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<p class="parrafo">Formulario de participación ciudadana y compromisos de la Defensoría del Pueblo de Colombia</p>

<Formulario />

<style>
	.parrafo {
		text-align: center;
	}
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
