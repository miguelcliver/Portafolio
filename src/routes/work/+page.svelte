<script>
  import Videos from "$lib/components/Videos.svelte";
</script>

<section class=" text-white px-6 pt-10 pb-12 md:px-16 lg:px-24 w-full">
  <div class="flex flex-col">
    <p
      class="font-sans text-[13vw] sm:text-[10vw] font-bold uppercase leading-[0.8] "
    >
      selected
    </p>
    <p
      class="font-sans text-[13vw] sm:text-[10vw] font-bold uppercase leading-[0.8] bg-linear-to-r from-[#00b0ff] via-[#448aff] to-[#9333ea] bg-clip-text text-transparent"
    >
      Project
    </p>
  </div>

  <div
    class="flex flex-col gap-8 m pt-4"
  >
    <div class="space-y-2 max-w-md ">
      <p
        class="font-mono text-xs font-bold tracking-widest text-blue-400 uppercase "
      >
        Selected Cuts 2022-24
      </p>
      <p
        class="font-sans text-sm font-light leading-relaxed text-gray-400 "
      >
        Una selección curada de piezas editoriales, comerciales y contenido
        short-form producidas para marcas y artistas.
      </p>
    </div>
  </div>
</section>

<section class="text-white px-6 py-12 md:px-16 lg:px-24 w-full">
    <div class="flex items-end justify-between border-b border-white/5 pb-4">
      <div class="space-y-1">
        <p
          class="font-mono text-[11px] font-bold tracking-widest text-[#00b0ff] uppercase"
        >
          01 / Bento Reel
        </p>
        <p
          class="font-sans text-3xl font-black tracking-wide  uppercase md:text-4xl"
        >
          Featured Cuts
        </p>
      </div>
    </div>
  
  <div
    class="flex flex-row overflow-x-auto pb-4  w-full gap-10"
  >
    <div
      class=" w-[85vw]  space-y-4 lg:w-auto lg:col-span-7 max-w-160 group px-6"
    >
      <div
        class="relative aspect-video w-full overflow-hidden rounded-3xl border border-white/10 bg-[#121214] shadow-[0_0_50px_rgba(147,51,234,0.03)] transition-all duration-300 group-hover:border-purple-500/30 group-hover:shadow-[0_0_40px_rgba(147,51,234,0.1)]"
      >
        <img
          src="/carro1.jpg"
          alt="Midnight Velocity"
          class="h-full w-full object-cover"
          loading="lazy"
        />
      </div>
      <div class="flex items-start justify-between px-1">
        <p
          class="font-sans text-xl font-black tracking-wide  uppercase transition-colors group-hover:text-cyan-400"
        >
          Midnight Velocity
        </p>
        <div
          class="flex flex-col items-end font-mono text-[10px] text-neutral-500 tracking-wider"
        >
          <p class="text-[#00b0ff] font-bold">2026</p>
          <p>16:9 — Commercial</p>
        </div>
      </div>
    </div>
    <div
      class="shrink-0 w-[85vw] snap-center space-y-4 lg:w-[38%] max-w-115 group"
    >
      <div
        class="relative aspect-video w-full overflow-hidden rounded-3xl border border-white/10 bg-[#121214] shadow-[0_0_50px_rgba(147,51,234,0.03)] transition-all duration-300 group-hover:border-blue-500/30 group-hover:shadow-[0_0_40px_rgba(59,130,246,0.1)]"
      >
        <img
          src="carro2.jpg"
          alt="Horizon Caliber"
          class="h-full w-full object-cover"
          loading="lazy"
        />
      </div>
      <div class="flex items-start justify-between px-1">
        <p
          class="font-sans text-xl font-black tracking-wide  uppercase transition-colors group-hover:text-blue-400"
        >
          Horizon Caliber
        </p>
        <div
          class="flex flex-col items-end font-mono text-[10px] text-neutral-500 tracking-wider"
        >
          <p class="text-[#00b0ff] font-bold">2026</p>
          <p>4:3 — Branding</p>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="w-full text-white px-6 py-16 ">
  <div class="mx-auto max-w-6xl space-y-12">
    <div class="relative space-y-2">
      <p class="font-mono text-xs font-black tracking-widest text-cyan-400">
        02/
      </p>
      <p
        class="font-sans text-[12vw] sm:text-[10vw] font-black tracking-tighter uppercase leading-[0.85]"
      >
        DEALER
        <span class="text-cyan-400">SHIP</span>
      </p>
    </div>

    <div
      class="flex gap-6 overflow-x-auto pb-4 lg:grid lg:grid-cols-3  w-full"
    >
      <div
        class="shrink-0 w-[75vw] sm:w-[45vw] snap-center lg:w-auto group flex flex-col gap-4"
      >
        <div
          class="relative aspect-9/16 w-full overflow-hidden rounded-4xl border border-white/5 bg-[#121214]/40 shadow-[0_0_50px_rgba(147,51,234,0.02)] backdrop-blur-md transition-all duration-300 group-hover:border-purple-500/30 group-hover:shadow-[0_0_40px_rgba(147,51,234,0.12)]"
        >
          <img
            src="carro3.jpg"
            alt="Velocity Black"
            class="h-full w-full object-cover"
            loading="lazy"
          />
          <div
            class="absolute inset-0 bg-linear-to-t from-black/80 via-transparent to-transparent opacity-90"
          ></div>

          <div
            class="absolute bottom-6 left-6 right-6 flex items-end justify-between z-10"
          >
            <p
              class="font-sans text-lg font-black tracking-wide  uppercase group-hover:text-purple-400 transition-colors"
            >
              Velocity Black
            </p>
            <p
              class="font-mono text-[10px] font-bold text-neutral-500 tracking-wider"
            >
              2025
            </p>
          </div>
        </div>
      </div>

      <div
        class="shrink-0 w-[75vw] sm:w-[45vw]  lg:w-auto group flex flex-col gap-4"
      >
        <div
          class="relative aspect-9/16 w-full overflow-hidden rounded-4xl border border-white/5 bg-[#121214]/40 shadow-[0_0_50px_rgba(147,51,234,0.02)] backdrop-blur-md transition-all duration-300 group-hover:border-blue-500/30 group-hover:shadow-[0_0_40px_rgba(59,130,246,0.12)]"
        >
          <img
            src="carro4.jpg"
            alt="Night Drive"
            class="h-full w-full object-cover"
          />
          <div
            class="absolute inset-0 bg-linear-to-t from-black/80 via-transparent to-transparent opacity-90"
          ></div>
          <div
            class="absolute bottom-6 left-6 right-6 flex items-end justify-between z-10"
          >
            <p
              class="font-sans text-lg font-black tracking-wide text-white uppercase group-hover:text-blue-400 transition-colors"
            >
              Night Drive
            </p>

            <p
              class="font-mono text-[10px] font-bold text-neutral-500 tracking-wider"
            >
              2024
            </p>
          </div>
        </div>
      </div>
      <div
        class="shrink-0 w-[75vw] sm:w-[45vw] snap-center lg:w-full group flex flex-col gap-4"
      >
        <div
          class="relative aspect-9/16 w-full overflow-hidden rounded-4xl border border-white/5 bg-[#121214]/40 shadow-[0_0_50px_rgba(147,51,234,0.02)] backdrop-blur-md transition-all duration-500 group-hover:border-purple-500/30 group-hover:shadow-[0_0_40px_rgba(147,51,234,0.12)]"
        >
          <img
            src="carro5.jpg"
            alt="Tunnel Vision"
            class="h-full w-full object-cover"
            loading="lazy"
          />
          <div
            class="absolute inset-0 bg-linear-to-t from-black/80 via-transparent to-transparent opacity-90"
          ></div>
          <div
            class="absolute bottom-6 left-6 right-6 flex items-end justify-between z-10"
          >
            <p
              class="font-sans text-lg font-black tracking-wide uppercase group-hover:text-purple-400 transition-colors"
            >
              Tunnel Vision
            </p>
            <p
              class="font-mono text-[10px] font-bold text-neutral-500 tracking-wider"
            >
              2024
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="w-full text-white px-6 py-16 md:px-16 lg:px-24">
  <div class="mx-auto max-w-6xl space-y-8">
    <div class="flex items-end justify-between border-b border-white/5 pb-4">
      <div class="space-y-1">
        <p
          class="font-mono text-[11px] font-bold tracking-widest text-[#00b0ff] uppercase"
        >
          04 / Director's Cut
        </p>
        <p
          class="font-sans text-3xl font-black tracking-wide  uppercase "
        >
          Premium Production
        </p>
      </div>
    </div>
  </div>
  <div
    class="group relative aspect-video w-full overflow-hidden rounded-4xl border border-white/10 bg-[#121214] shadow-[0_0_60px_rgba(147,51,234,0.04)]"
  >
    <img
      src="carro6.jpg"
      alt="Taste of Noir"
      class="h-full w-full object-cover"
      loading="lazy"
    />
    <div
      class="absolute inset-0 bg-linear-to-t from-black/90 via-black/20 to-transparent pointer-events-none"
    ></div>
    <div
      class="absolute bottom-6 left-6 right-6 md:bottom-10 md:left-10 md:right-10 z-20 flex flex-col gap-4 md:flex-row md:items-end md:justify-between"
    >
      <div class="space-y-2">
        <p
          class="block font-mono text-xs font-bold text-cyan-400 tracking-wider uppercase"
        >
          Savore — 2025
        </p>
        <p
          class="font-sans text-4xl sm:text-5xl md:text-6xl font-black tracking-tighter uppercase leading-none t"
        >
          Taste of
          <span
            class="bg-linear-to-r from-cyan-400 via-purple-500 to-pink-500 bg-clip-text text-transparent"
            >Noir</span
          >
        </p>
      </div>
    </div>
  </div>
</section>
