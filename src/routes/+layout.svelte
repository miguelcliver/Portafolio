<script lang="ts">
  import "./layout.css";
  import favicon from "$lib/assets/favicon.svg";
  import Icon from "@iconify/svelte";

  let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<nav>
  <p>MIKE EDITOR</p>
  <div>
    <a href="/">menu</a>
    <a href="/work">Portafolio</a>
  </div>
  <a href="/contact">
    <button>Contacto</button>
  </a>
</nav>

{@render children()}

<footer>
  <div>
    <p>MIKE EDITOR</p>
    <p>Todos los derechos reservados</p>
  </div>
  <div>
    <a href="https://www.instagram.com/?hl=es"><Icon icon="skill-icons:instagram" width={32} height={32}/></a>
    <a href="https://www.whatsapp.com/?lang=es"><Icon icon="logos:whatsapp-icon" width={32} height={32}/></a>
    <a href="https://ve.linkedin.com/"><Icon icon="skill-icons:linkedin" width={32} height={32} /></a>
    </div>
  <div>
    <p>estado disponible</p>
    <p>work@thefame.pro</p>
  </div>
</footer>
