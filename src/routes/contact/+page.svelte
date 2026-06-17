<script>

  let nombreEmpresa = $state()
  let email = $state()
  let concepto = $state()

  function EnviarPropuesta () {
    window.open(`https://api.whatsapp.com/send/?phone=584244315969&text=Hola, le escribe ${nombreEmpresa} - ${email}, ${concepto}`)
  }

</script>

<section class=" text-white px-20 pt-10 pb-12 md:px-16 lg:px-24 w-full  border-0 border-b border-neutral-800">
  <div class=" flex flex-col">
    <p
      class="font-sans text-9xl font-black tracking-tighter leading-[0.85] uppercase px-30"
    >
      Trabajemos<br> <span class="text-cyan-400 ">Juntos</span>
    
    </p>
  </div>
</section>

<section class="w-full text-white px-6 py-10  border-0 border-b border-neutral-800 ">
  <div class="max-w-300 mx-auto grid grid-cols-1 md:grid-cols-3 gap-10">
    <div class="flex flex-col">
      <p
        class="font-mono text-[11px] font-bold text-[#00F0FF] uppercase tracking-[0.15em] mb-3.5"
      >
        [ UBICACIÓN ]
      </p>
      <p class="font-mono text-[15px] leading-relaxed font-medium">
        Studio 04 — Calle Serrano 41<br />
        Madrid, ES - 28001
      </p>
    </div>
    <div class="flex flex-col">
      <p
        class="font-mono text-[11px] font-bold text-[#00F0FF] uppercase tracking-[0.15em] mb-3.5"
      >
        [ DISPONIBILIDAD ]
      </p>
      <p class="font-mono text-[15px] font-medium">
        Lunes a viernes • 09:00 - 19:00 CET
      </p>
      <p class="font-mono text-[13px] text-[#8a8a93] mt-1">
        Respuesta en 24 horas
      </p>
    </div>
    <div class="flex flex-col">
      <p
        class="font-mono text-[11px] font-bold text-[#00F0FF] uppercase tracking-[0.15em] mb-3.5"
      >
        [ SOCIAL ]
      </p>
      <div class="flex flex-wrap gap-2 max-w-85">
        <a
          href="https://www.instagram.com/?hl=es"
          class="font-mono text-[11px] font-bold tracking-wider text-[#8a8a93] px-4 py-2 rounded-full border border-white/10 bg-white/2 backdrop-blur-sm transition-all duration-300 hover:border-[#9333EA] hover:text-[#9333EA] hover:shadow-[0_0_10px_rgba(147,51,234,0.15)] flex items-center gap-1.5"
        >
          📸 INSTAGRAM
        </a>
        <a
          href="https://ve.linkedin.com/"
          class="font-mono text-[11px] font-bold tracking-wider text-[#8a8a93] px-4 py-2 rounded-full border border-white/10 bg-white/2 backdrop-blur-sm transition-all duration-300 hover:border-[#9333EA] hover:text-[#9333EA] hover:shadow-[0_0_10px_rgba(147,51,234,0.15)] flex items-center gap-1.5 mt-1"
        >
          💼 LINKEDIN
        </a>
        <a
          href="https://wa.me"
          target="_blank"
          rel="noopener noreferrer"
          class="font-mono text-[11px] font-bold tracking-wider text-[#8a8a93] px-4 py-2 rounded-full border border-white/10 bg-white/2 backdrop-blur-sm transition-all duration-300 hover:border-[#9333EA] hover:text-[#9333EA] hover:shadow-[0_0_10px_rgba(147,51,234,0.15)] flex items-center gap-1.5"
        >
          💬 WHATSAPP
        </a>
      </div>
    </div>
  </div>
</section>

<section class="w-full text-white px-6 py-16 border-0 border-b border-neutral-800">
  <div
    class="max-w-300 mx-auto grid grid-cols-1 lg:grid-cols-[4fr_7fr] gap-16 lg:gap-20"
  >
    <div class="flex flex-col">
      <p
        class="text-[clamp(2.5rem,5vw,4.2rem)] font-black uppercase leading-[0.95] tracking-tight mb-6"
      >
        CONSTRUYAMOS TU VISIÓN.
      </p>
      <p class="font-mono text-[13px] text-[#8a8a93] leading-relaxed max-w-85">
        Cuéntanos la historia que quieres contar. Respondemos personalmente a cada solicitud en un plazo de un día hábil.
      </p>
    </div>
    <form class="w-full flex flex-col justify-between" onsubmit={EnviarPropuesta}>
      <div class="flex flex-wrap gap-x-6 gap-y-10">
        <div class="flex flex-col flex-1 min-w-62.5">
          <label
            for="NAME/COMPANY"
            class="font-mono text-[11px] font-bold text-[#00F0FF] uppercase tracking-[0.15em] mb-3"
            >[ NOMBRE / EMPRESA ]</label
          >
          <input
            type="text"
            placeholder="Nombre de la empresa "
            required
            bind:value={nombreEmpresa}
            class="bg-transparent border-0 border-b border-[#4a4a52] py-2 font-mono text-[14px] placeholder-[#4a4a52] outline-none transition-colors duration-300 focus:border-[#00F0FF] rounded-none"
          />
        </div>
        <div class="flex flex-col flex-1 min-w-62.5">
          <label
            for="EMAIL"
            class="font-mono text-[11px] font-bold text-[#00F0FF] uppercase tracking-[0.15em] mb-3"
            >[ EMAIL ]</label
          >
          <input
            type="email"
            placeholder="hello@yourbrand.com"
            required
            bind:value={email}
            autocomplete="new-password"
            class="bg-transparent border-0 border-b border-[#4a4a52] py-2 font-mono text-[14px] text-white placeholder-[#4a4a52] outline-none transition-colors duration-300 focus:border-[#00F0FF] rounded-none
            autofill:shadow-[inset_0_0_0_1000px_#050508] autofill:text-white"
          />
        </div>
        <div class="flex flex-col w-full">
          <label
            for="PROJECT TYPE"
            class="font-mono text-[11px] font-bold text-[#00F0FF] uppercase tracking-[0.15em] mb-3"
            >[ TIPO DE PROYECTO  ]</label>
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-3 w-full">
              <label class="cursor-pointer group select-none">
                <input type="radio" name="project_type" value="reels" class="peer sr-only" checked />
                <div class="font-mono text-[14px] text-center text-[#8a8a93] py-3 px-4 border bg-white/1 backdrop-blur-sm transition-all duration-300 rounded-none border-b border-[#4a4a52] peer-checked:border-[#339bea] peer-checked:text-[#00F0FF] peer-checked:bg-[#9333EA]/10 peer-checked:shadow-[0_0_15px_rgba(147,51,234,0.15)] hover:border-white/30">
                  Reels / Shorts / TikToks
                </div>
              </label>
              <label class="cursor-pointer group select-none">
                <input type="radio" name="project_type" value="commercial" class="peer sr-only" />
                <div class="font-mono text-[14px] text-center text-[#8a8a93] py-3 px-4 border bg-white/1 backdrop-blur-sm transition-all duration-300 rounded-none border-b border-[#4a4a52] peer-checked:border-[#339bea]  peer-checked:text-[#00F0FF] peer-checked:bg-[#9333EA]/10 peer-checked:shadow-[0_0_15px_rgba(147,51,234,0.15)] hover:border-white/30">
                  Premium Commercial
                </div>
              </label>
              <label class="cursor-pointer group select-none">
                <input type="radio" name="project_type" value="corporate" class="peer sr-only" />
                <div class="font-mono text-[14px] text-center text-[#8a8a93] py-3 px-4 border bg-white/1 backdrop-blur-sm transition-all duration-300 rounded-none border-b border-[#4a4a52] peer-checked:border-[#339bea] peer-checked:text-[#00F0FF] peer-checked:bg-[#9333EA]/10 peer-checked:shadow-[0_0_15px_rgba(147,51,234,0.15)] hover:border-white/30">
                  Corporate Video
                </div>
              </label>

            </div>
          

        </div>
        <div class="flex flex-col w-full">
          <label
            for="PROJECT DETAIL"
            class="font-mono text-[11px] font-bold text-[#00F0FF] uppercase tracking-[0.15em] mb-3"
            >[ DETALLES DEL PROYECTO ]</label
          >
          <textarea
            placeholder="Concepto, referencias, cronograma, rango de presupuesto..."
            rows="3"
            required
            bind:value={concepto}
            class="bg-transparent border-0 border-b border-[#4a4a52] py-2 font-mono text-[14px] placeholder-[#4a4a52] outline-none transition-colors duration-300 focus:border-[#00F0FF] rounded-none resize-none"
          ></textarea>
        </div>
        <div class="w-full flex justify-end mt-2">
          <button
            type="submit"
            class="group inline-flex items-center gap-3 bg-linear-to-r from-[#00F0FF] to-[#9333EA] font-sans font-black text-[13px] uppercase tracking-wider px-8 py-3.5 rounded-[28px] cursor-pointer transition-all duration-300 hover:-translate-y-0.5 hover:shadow-[0_8px_25px_rgba(0,240,255,0.3),0_8px_25px_rgba(147,51,234,0.3)]"
          >
           ENVIAR
            <span
              class="text-sm transition-transform duration-300 group-hover:translate-x-1"
              >→</span
            >
          </button>
        </div>
      </div>
    </form>
  </div>
</section>
