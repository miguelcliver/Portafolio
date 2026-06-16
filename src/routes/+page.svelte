<script>
  // @ts-nocheck

  import Software from "$lib/components/Software.svelte";
  import Tarjetadehabilidades from "$lib/components/Tarjetadehabilidades.svelte";
  import Icon from "@iconify/svelte";
</script>

<section class="px-20 py-15 text-white border-0 border-b border-neutral-800 ">
<div class="flex flex-wrap gap-3 mb-10 select-none">
  <div class="font-mono text-[12px] font-bold tracking-widest text-[#00F0FF] px-4 py-2.5 rounded-full border border-[#00F0FF]/20 bg-[#00F0FF]/5 backdrop-blur-sm cursor-default flex items-center gap-1.5">
    ⚡ DISPONIBLE PARA TRABAJAR
  </div>
  <div class="font-mono text-[12px] font-bold tracking-widest text-[#8a8a93] px-4 py-2.5 rounded-full border border-white/5 bg-white/2 backdrop-blur-sm cursor-default flex items-center gap-1.5">
    🎬 REELS & COMMERCIALS
  </div>
</div>
  <p
    class=" font-sans text-5xl md:text-7xl lg:text-8xl font-black uppercase text-left tracking-tighter leading-[0.85]"
  >
   profesional  video  <br />
   <span class="bg-linear-to-r from-[#00F0FF] to-[#30cbff] bg-clip-text text-transparent">
     editor
   </span>
  </p>
  <div class="flex justify-end mt-12">
    <div class="relative pl-8">
      <div
        class="absolute bottom-4 left-4 top-2 w-0.5 bg-linear-to-b from-blue-600 via-cyan-600 to-transparent"
      ></div>
    </div>
    <div class="relative mb-6">
      <p class="font-mono text-[14px] font-bold text-[#00F0FF] pb-3 uppercase tracking-wider">Michael Montañez</p>
      <p class="max-w-xl text-neutral-200">
        Hola, soy Michael  Ayudo a empresas a comunicar sus ideas con videos claros, atractivos y de alta calidad. Si buscas un trabajo profesional, puntual y adaptado a tus metas, hagamos equipo en tu próximo proyecto.
      </p>
      <a href="/work" class="group font-mono text-[12px] font-bold text-[#00F0FF] tracking-wider uppercase inline-flex items-center gap-2 transition-colors duration-300 hover:text-blue-300 ">
        VER TRABAJOS SELECCIONADOS
        <span class="transition-transform duration-300 group-hover:translate-x-1.5">→</span>
      </a>
    </div>
  </div>
</section>

<section
  class="flex gap-12 items-center px-20 py-15 bg-transparent text-white  border-0 border-b border-neutral-800"
>
  <div class="space-y-7 space-x-2">
    <p class="text-5xl font-black uppercase tracking-wider px-10">
      Mi historia
    </p>

    <img
      src="/mi-historia.jpeg"
      alt="foto"
      width="400"
      height="400"
      class="rounded-3xl border border-neutral-700 "
    />
  </div>

  <div class="space-y-7">
    <p class="max-w-lvh text-neutral-300 ml-3">
      Empecé en el mundo de la edición por curiosidad y por querer aprender algo nuevo. Al percatarme de que es algo que realmente me apasiona, comencé a realizar trabajos pequeños y, desde hace aproximadamente dos años y siete meses, trabajo de forma profesional.
    </p>

    <div class="relative pl-8">
      <div
        class="absolute -bottom-4 left-4 top-2 w-0.5 bg-linear-to-b from-blue-600 via-cyan-600 to-transparent"
      ></div>

      <div class="relative mb-6">
        <p class="text-[#00F0FF]">2014-2018</p>
        <p>Inicios en montaje documental y colorimetría básica.</p>
      </div>
      <div>
        <p class="text-[#00F0FF]">2019- presente</p>
        <p>
          Especialización en postproducción técnica y narrativa para marcas globales.
        </p>
      </div>
    </div>
  </div>
</section>

<section class="w-full  text-white border-0 border-b border-neutral-800 py-16 font-sans">
  <div class="py-8 px-20 text-4xl font-black uppercase tracking-tighter select-none font-sans text-center ">
    <p>HABILIDADES</p>
    <div class="w-16 h-1 bg-cyan-600 mx-auto mt-4 rounded-full"></div>
  </div>
  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 px-20">
    <div class="">
    <Tarjetadehabilidades
      titulo="Manejo de plataformas"
      descripcion="Domino las herramientas líderes de la industria audiovisual, con un manejo experto de Adobe Premiere Pro y CapCut."
      icono="lucide:video"
    />
    </div>
    <div >
    <Tarjetadehabilidades
      titulo="Adaptacion a diferentes estilos"
      descripcion="Cuento con una alta capacidad de adaptación para moldear el estilo de edición según las necesidades de cada proyecto, ya sea contenido corporativo, publicitario o dinámico para redes."
      icono="lucide:wand-2"
    />
    </div>
    <div>
    <Tarjetadehabilidades
      titulo="Conocimientos de tendencias"
      descripcion="Me mantengo a la vanguardia de la industria audiovisual, monitoreando constantemente las tendencias y técnicas actuales de edición en redes sociales. "
      icono="lucide:trending-up"
    />
    </div>
   
  </div>
</section>

<section class="py-20 px-8 border-0 border-b border-neutral-800 text-white">
  <div class="flex flex-col items-center gap-12">
  <div class="py-8 px-12 text-4xl font-black uppercase  select-none font-sans text-center">
    <p
    >
      SOFTWARE
    </p>
    <div class="w-16 h-1 bg-cyan-600 mx-auto mt-4 rounded-full"></div>
  </div>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-12 sm:gap-16 md:gap-24 max-w-3xl mx-auto">
      <div
        class="group flex flex-col items-center justify-center text-center cursor-pointer relative"
      >
      <div class="absolute -top-4 w-20 h-20 bg-[#00D8F6]/10 rounded-full blur-xl opacity-0 group-hover:opacity-100 transition-opacity duration-300 pointer-events-none"></div>
        
    
      <div class="text-zinc-500 group-hover:text-[#00D8F6] group-hover:scale-110 transition-all duration-300 mb-3 relative z-10">
        <Icon icon="hugeicons:capcut" class="text-4xl sm:text-5xl" />
      </div>
        <p class=" font-sans text-sm font-black text-zinc-400 group-hover:text-white uppercase tracking-wide transition-colors relative z-10">CAPCUT PRO</p>
      </div>
      <div
        class="group flex flex-col items-center justify-center text-center cursor-pointer relative" 
      >
      <div class="absolute -top-4 w-20 h-20 bg-[#00D8F6]/10 rounded-full blur-xl opacity-0 group-hover:opacity-100 transition-opacity duration-300 pointer-events-none"></div>

      <div class="text-zinc-500 group-hover:text-[#00D8F6] group-hover:scale-110 transition-all duration-300 mb-3 relative z-10">
        <Icon icon="hugeicons:adobe-premier" class="text-4xl sm:text-5xl" />
      </div>
        <p class="font-sans text-sm font-black text-zinc-400 group-hover:text-white uppercase tracking-wide transition-colors relative z-10">PREMIERE PRO</p>
      </div>
      <div
        class="group flex flex-col items-center justify-center text-center cursor-pointer relative"
      >
       <div class="absolute -top-4 w-20 h-20 bg-[#00D8F6]/10 rounded-full blur-xl opacity-0 group-hover:opacity-100 transition-opacity duration-300 pointer-events-none"></div>
       <div class="text-zinc-500 group-hover:text-[#00D8F6] group-hover:scale-110 transition-all duration-300 mb-3 relative z-10">
        <Icon icon="hugeicons:adobe-after-effect" class="text-4xl sm:text-5xl" />
       </div>
        <p class="font-sans text-sm font-black text-zinc-400 group-hover:text-white uppercase tracking-wide transition-colors relative z-10">AFTER EFFECTS</p>
      </div>
    </div>
  </div>
</section>

<section class="w-full bg-black text-white py-24 px-6 sm:px-12 md:px-24 font-sans border-b border-neutral-800 relative overflow-hidden select-none">
  <div class="absolute inset-0 bg-[linear-gradient(to_right,#ffffff02_1px,transparent_1px),linear-gradient(to_bottom,#ffffff03_1px,transparent_1px)] bg-size-[32px_32px] pointer-events-none"></div>
  <div
    class="max-w-5xl mx-auto flex flex-col md:flex-row items-center justify-center gap-12 md:gap-16 relative z-10"
  >
    <div
      class="relative aspect-9/16 w-full max-w-85 mx-auto overflow-hidden rounded-4xl border border-white/10 bg-[#121214] shadow-[0_0_50px_rgba(147,51,234,0.2)]"
    >
      <video controls class="h-full w-full object-cover"
      loading="lazy">
        <source src="/video-page.mp4" />
      </video>
    </div>

    <div class="flex flex-col items-center md:items-start text-center md:text-left max-w-md group">
      <span class="text-xs font-mono text-[#00D8F6] tracking-[0.3em] uppercase block mb-3">// PORTFOLIO_FEATURE</span>
       
          <p class=" text-2xl font-mono uppercase tracking-widest mb-4">
            Trabajos destacados
          </p>
          <div class="space-y-4">
            <p
              class="text-4xl sm:text-5xl font-black uppercase tracking-tighter leading-none mb-6 bg-clip-text text-transparent bg-linear-to-r from-white via-zinc-100 to-zinc-400 group-hover:from-white group-hover:via-white group-hover:to-[#00D8F6] transition-all duration-500"
            >
              Ritmo cinematico
            </p>
            <p class="text-sm font-mono text-zinc-400 leading-relaxed mb-8 max-w-sm">
              Edición dinámica con cortes precisos al ritmo del beat, corrección de color estilizada y diseño sonoro envolvente para máxima retención.
            </p>
      
          <a
            href="/work"
            class="inline-flex items-center gap-2 font-mono text-xs font-bold tracking-widest text-cyan-400 hover:text-blue-300 transition-colors uppercase"
            >ver archivo completo</a
          >
          </div>
        </div>
      </div>
</section>
