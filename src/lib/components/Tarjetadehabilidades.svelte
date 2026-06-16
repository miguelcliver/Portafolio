<script>
    const {titulo,descripcion,icono} = $props()
    import Icon from "@iconify/svelte";
</script>

<div class="p-8 bg-[#0a0a0f]/40 backdrop-blur-md border border-white/5 rounded-2xl flex flex-col justify-between min-h-55 transition-all duration-300 hover:border-[#00D8F6]/30 hover:bg-[#00D8F6]/5 hover:shadow-[0_0_40px_rgba(0,216,246,0.1)] group select-none h-full ">
<div class="space-y-3">
    <p class="font-sans text-xl md:text-2xl font-black text-white tracking-tight leading-snug group-hover:text-[#E0F2FE] transition-colors ">{titulo}</p>
    <p class="font-sans text-[13px] md:text-[14px] text-[#a1a1aa] leading-relaxed group-hover:text-[#f4f4f5] transition-colors">{descripcion}</p>
    <div class="w-12 h-12 bg-[#00D8F6]/10 rounded-xl flex items-center justify-center text-[#00D8F6] group-hover:bg-[#00D8F6] group-hover:text-black transition-all duration-300 mb-2">
    <Icon icon={icono} class="w-6 h-6" />
</div>
</div>
</div>