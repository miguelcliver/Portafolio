<script lang="ts">
  import "./layout.css";
  import favicon from "$lib/assets/favicon.svg";
  import Icon from "@iconify/svelte";

  let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<nav class="flex justify-between items-center px-12 py-4">
  <p class="text-xl font-black tracking-wider text-white">MIKE <span class="bg-linear-to-r from-blue-400 to-indigo-500 bg-clip-text text-transparent">EDITOR</span></p>

  <div class="flex items-center gap-8 bg-white/3 px-6 py-2.5 rounded-full border border-white/10 backdrop-blur-xl">
    <a href="/" class="relative py-1 text-sm font-medium text-neutral-300 hover:text-white transition-colors group">Home<span class="absolute bottom-0 left-0 w-0 h-[1.5px] bg-blue-400 transition-all duration-300 group-hover:w-full"></span></a>
    <a href="/work" class="relative py-1 text-sm font-medium text-neutral-300 hover:text-white transition-colors group">Portafolio<span class="absolute bottom-0 left-0 w-0 h-[1.5px] bg-blue-400 transition-all duration-300 group-hover:w-full"></span></a>
  </div>
  <a href="/contact" class="relative inline-flex items-center justify-center px-6 py-2.5 text-sm font-semibold text-white bg-linear-to-r from-blue-600 to-indigo-600 hover:from-blue-500 hover:to-indigo-500 rounded-full overflow-hidden transition-all hover:shadow-[0_0_20px_rgba(59,130,246,0.4)]">
    Contacto
  </a>
</nav>

{@render children()}

<footer class="flex justify-between items-center px-12 py-3">
  <div>
    <p class="text-white font-bold text-lg tracking-wide uppercase">MIKE EDITOR</p>
    <p class="text-xs text-neutral-500 font-medium">©MIKE EDITOR.Todos los derechos reservados.</p>
  </div>
  <div class="flex items-center gap-4 bg-neutral-900/40 p-2 px-4 border border-neutral-800/40 rounded-full backdrop-blur-sm shadow-inner group">
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
    <p class="text-blue-400">estado disponible</p>
    <p>work@thefame.pro</p>
  </div>
</footer>
