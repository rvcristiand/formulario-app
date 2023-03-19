<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/defensoria-pueblo.png';
	import github from '$lib/images/github.svg';
</script>

<header>
	<div class="corner">
		<a href="https://www.defensoria.gov.co/">
			<img src={logo} alt="Defensoría del Pueblo de Colombia" />
		</a>
	</div>

	<h1 class="titulo">
		Formulario de participación ciudadana y compromisos de la Defensoría del Pueblo de Colombia
	</h1>

	<div class="corner">
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: center;
	}

	.corner {
		position: absolute;
		left: 0;
	}

	.corner a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

	.corner img {
/*  		width: 2em; */
		padding: 1em 0 1em 1em;
		height: 10em;
		object-fit: contain;
	}

 	.titulo {
		display: flex;
		justify-content: center;
		--background: rgba(255, 255, 255, 0.7);
		max-width: 30em;
	}

	svg {
		width: 2em;
		height: 3em;
		display: block;
	}

	path {
		fill: var(--background);
	}

	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	li[aria-current='page']::before {
		--size: 6px;
		content: '';
		width: 0;
		height: 0;
		position: absolute;
		top: 0;
		left: calc(50% - var(--size));
		border: var(--size) solid transparent;
		border-top: var(--size) solid var(--color-theme-1);
	}

	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 0.5rem;
		color: var(--color-text);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;
	}

	a:hover {
		color: var(--color-theme-1);
	}
</style>
