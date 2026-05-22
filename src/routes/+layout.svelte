<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<nav>
	<p>The frame</p>
	<div>
	<a href="/">menu</a>
	<a href="/word">Work</a>
	</div>
<a href="/contact">
<button>Contacto</button>
</a>
</nav>


{@render children()}

<footer>
	<div>
		<img src="" alt="">
		<p>Todos los derechos reservados</p>
	</div>
	<div>
		<a href="https://www.instagram.com/?hl=es">instagram</a>
		<a href="https://vimeo.com/es">vimeo</a>
		<a href="https://ve.linkedin.com/">linkedin</a>
	</div>
	<div>
		<p>estado disponible</p>
		<p>work@thefame.pro</p>
	</div>
</footer>
