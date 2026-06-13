<script>
  // @ts-nocheck

  import Software from "$lib/components/Software.svelte";
  import Tarjetadehabilidades from "$lib/components/Tarjetadehabilidades.svelte";
  import Icon from "@iconify/svelte";
</script>

<section class="px-9 py-15 text-white border-0 border-b border-neutral-800 ">
<div class="flex flex-wrap gap-3 mb-10 select-none">
  <div class="font-mono text-[12px] font-bold tracking-widest text-[#00F0FF] px-4 py-2.5 rounded-full border border-[#00F0FF]/20 bg-[#00F0FF]/5 backdrop-blur-sm cursor-default flex items-center gap-1.5">
    ⚡ AVAILABLE FOR WORK
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
        Hola, soy Michael. Ayudo a empresas a comunicar sus ideas con videos
        claros, atractivos y de alta calidad. Si buscas un trabajo profesional,
        puntual y adaptado a tus metas, hagamos equipo en tu próximo proyecto.
      </p>
      <a href="/work" class="group font-mono text-[12px] font-bold text-[#00F0FF] tracking-wider uppercase inline-flex items-center gap-2 transition-colors duration-300 hover:text-[#9333EA]">
        VIEW SELECTED WORK 
        <span class="transition-transform duration-300 group-hover:translate-x-1.5">→</span>
      </a>
    </div>
  </div>
</section>

<section
  class="flex gap-12 items-center px-20 py-15 bg-transparent text-white "
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
      Empece en el mundo de edicion por curiosidad y por querer aprender algo
      nuevo, percatándome de que es algo q me gusta, empecé a realizar trabajos
      pequeños y ya hace aproximadamente 2 años y 7 meses trabajando
      profesionalmente.
    </p>

    <div class="relative pl-8">
      <div
        class="absolute -bottom-4 left-4 top-2 w-0.5 bg-linear-to-b from-blue-600 via-cyan-600 to-transparent"
      ></div>

      <div class="relative mb-6">
        <p class="text-[#00F0FF]">2014-2018</p>
        <p>inicios en montaje documental y colorimetrica basica.</p>
      </div>
      <div>
        <p class="text-[#00F0FF]">2019- presente</p>
        <p>
          especialización en postproducción técnica y narrativa para marcas
          globales.
        </p>
      </div>
    </div>
  </div>
</section>

<section class="w-full bg-[#050508] text-white border-t border-white/10 py-16">
  <div class="py-8 px-12 text-4xl font-black uppercase tracking-tighter select-none font-sans text-center ">
    <p>HABILIDADES</p>
  </div>
  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 px-12">
    <div class="">
    <Tarjetadehabilidades
      titulo="Manejo de plataformas"
      descripcion="Domino las herramientas líderes de la industria audiovisual, con un manejo experto de Adobe Premiere Pro y CapCut."
    />
    </div>
    <div >
    <Tarjetadehabilidades
      titulo="Adaptacion a diferentes estilos"
      descripcion="Cuento con una alta capacidad de adaptación para moldear el estilo de edición según las necesidades de cada proyecto, ya sea contenido corporativo, publicitario o dinámico para redes."
    />
    </div>
    <div>
    <Tarjetadehabilidades
      titulo="Conocimientos de tendencias"
      descripcion="Me mantengo a la vanguardia de la industria audiovisual, monitoreando constantemente las tendencias y técnicas actuales de edición en redes sociales. "
    />
    </div>
   
  </div>
</section>

<section class="py-20 px-8 border border-neutral-600/40 text-white">
  <div class="flex flex-col items-center gap-12">
    <p
      class="font-sans text-4xl font-extrabold tracking-wider  md:text-5xl uppercase text-center"
    >
      SOFTWARE
    </p>

    <div class="flex gap-22 px-21 py-10">
      <div
        class="flex items-center justify-center rounded-xl border border-cyan-500/40 bg-[#121214] px-8 py-10 shadow-[inset_0_0_20px_rgba(6,182,212,0.08)]"
      >
        <p class=" ">CAPCUT PRO</p>
      </div>
      <div
        class="flex items-center justify-center rounded-xl border border-purple-600/40 bg-[#121214] px-8 py-10 shadow-[inset_0_0_20px_rgba(147,51,234,0.08)]"
      >
        <p>PREMIERE PRO</p>
      </div>
      <div
        class="flex items-center justify-center rounded-xl border border-indigo-500/40 bg-[#121214] px-8 py-10 shadow-[inset_0_0_20px_rgba(99,102,241,0.08)]"
      >
        <p>AFTER EFFECTS</p>
      </div>
    </div>
  </div>
</section>

<section class="w-full px-6 py-20 text-white md:px-16 lg:px-24">
  <div
    class="mx-auto max-w-6xl flex flex-col gap-10 lg:flex-row lg:items-center lg:justify-center"
  >
    <div
      class="relative aspect-9/16 w-full max-w-85 mx-auto overflow-hidden rounded-4xl border border-white/10 bg-[#121214] shadow-[0_0_50px_rgba(147,51,234,0.2)]"
    >
      <video controls class="h-full w-full object-cover"
      loading="lazy">
        <source src="/video-page.mp4" />
      </video>
    </div>

    <div class="w-full lg:w-6/12 flex flex-col justify-center">
      <div
        class="rounded-[28px] border border-purple-600/10 bg-[#121214]/90 p-8 md:p-10 shadow-[inset_0_0_30px_rgba(147,51,234,0.03)] space-y-8 backdrop-blur-md"
      >
        <div class="">
          <p class=" text-xl font-bold tracking-widest uppercase">
            Trabajos destacados
          </p>
          <a
            href="/work"
            class="inline-flex items-center gap-2 font-mono text-xs font-bold tracking-widest text-purple-400 hover:text-purple-300 transition-colors uppercase"
            >ver archivo completo</a
          >
          <div class="space-y-4">
            <p
              class="font-sans text-4xl font-black tracking-wide uppercase leading-none md:text-5xl"
            >
              Ritmo cinematico
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
