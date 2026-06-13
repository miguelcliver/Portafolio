<script>
    const {titulo,descripcion} = $props()
</script>

<div class="p-8 bg-[#0a0a0f]/40 backdrop-blur-md border border-white/5 rounded-2xl flex flex-col justify-between min-h-55 transition-all duration-300 hover:border-[#9333EA]/30 hover:bg-[#9333EA]/5 hover:shadow-[0_0_40px_rgba(147,51,234,0.1)] group select-none ">
<div class="space-y-3">
    <p class="font-sans text-xl md:text-2xl font-black text-white tracking-tight leading-snug ">{titulo}</p>
    <p class="font-sans text-[13px] md:text-[14px] text-[#8a8a93] leading-relaxed">{descripcion}</p>
</div>
</div>