<script lang="ts">
  import "./layout.css";
  import favicon from "$lib/assets/favicon.svg";
  import Icon from "@iconify/svelte";

  let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<nav class="flex justify-between items-center px-12 py-4">
  <p class="text-2xl font-bold ">MIKE EDITOR</p>
  <div class="flex gap-3 text-neutral-300">
    <a href="/">Home</a>
    <a href="/work">Portafolio</a>
  </div>
  <a href="/contact">
    <button class="font-bold px-6 py-1.5 text-white border-2 border-white ">Contacto</button>
  </a>
</nav>

{@render children()}

<footer class="flex justify-between items-center px-12 py-3">
  <div>
    <p class="text-2xl font-bold">MIKE EDITOR</p>
    <p class="text-neutral-300">©MIKE EDITOR.Todos los derechos reservados.</p>
  </div>
  <div class="flex gap-5">
    <a href="https://www.instagram.com/?hl=es"
      ><Icon icon="skill-icons:instagram" width={32} height={32} /></a
    >
    <a href="https://www.whatsapp.com/?lang=es"
      ><Icon icon="logos:whatsapp-icon" width={32} height={32} /></a
    >
    <a href="https://ve.linkedin.com/"
      ><Icon icon="skill-icons:linkedin" width={32} height={32} /></a
    >
  </div>
  <div>
    <p class="text-[#00E1AB]">estado disponible</p>
    <p>work@thefame.pro</p>
  </div>
</footer>
