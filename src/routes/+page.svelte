<script>
  // @ts-nocheck

  import Software from "$lib/components/Software.svelte";
  import Tarjetadehabilidades from "$lib/components/Tarjetadehabilidades.svelte";
  import Icon from "@iconify/svelte";
</script>

<section class="px-9 py-8 border border-neutral-600/40">
  <p
    class="text-5xl md:text-7xl lg:text-8xl font-black uppercase text-left text-white tracking-tighter leading-[0.85] "
  >
    Editor de video <br />
    <span
      class="bg-linear-to-r from-blue-400 via-indigo-400 to-purple-500 bg-clip-text text-transparent"
    >
      Profesional
    </span>
  </p>

  <div class="flex justify-end">
    <div class="relative pl-8">
      <div
        class="absolute bottom-4 left-4 top-2 w-0.5 bg-linear-to-b from-blue-600 via-purple-600 to-transparent"
      ></div>
    </div>
    <div class="relative mb-6">
      <p class="text-blue-400 pb-4">Michael Montañez</p>
      <p class="max-w-xl text-neutral-200">
        Hola, soy Michael. Ayudo a empresas a comunicar sus ideas con videos
        claros, atractivos y de alta calidad. Si buscas un trabajo profesional,
        puntual y adaptado a tus metas, hagamos equipo en tu próximo proyecto.
      </p>
    </div>
  </div>
</section>

<section
  class="flex gap-12 items-center px-10 py-20 bg-transparent text-white border border-neutral-600/40"
>
  <div class="space-y-8">
    <p class="text-5xl font-black uppercase tracking-wider text-white px-17">
      Mi historia
    </p>
    
    <img
      src="/mi-historia.jpeg"
      alt="foto"
      width="500"
      height="500"
      class="rounded-3xl  "
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
        class="absolute -bottom-4 left-4 top-2 w-0.5 bg-linear-to-b from-blue-600 via-purple-600 to-transparent"
      ></div>

      <div class="relative mb-6">
        <p class="text-blue-400">2014-2018</p>
        <p>inicios en montaje documental y colorimetrica basica.</p>
      </div>
      <div>
        <p class="text-blue-400">2019- presente</p>
        <p>
          especialización en postproducción técnica y narrativa para marcas
          globales.
        </p>
      </div>
    </div>
  </div>
</section>

<section class="border border-neutral-600/40">
  <div class="py-8 px-15 text-4xl font-bold">
    <p>HABILIDADES</p>
  </div>
  <div class="grid grid-cols-3 px-12">
    <Tarjetadehabilidades
      titulo="Manejo de plataformas"
      descripcion="Domino las herramientas líderes de la industria audiovisual, con un manejo experto de Adobe Premiere Pro y CapCut."
    />
    <Tarjetadehabilidades
      titulo="Adaptacion a diferentes estilos"
      descripcion="Cuento con una alta capacidad de adaptación para moldear el estilo de edición según las necesidades de cada proyecto, ya sea contenido corporativo, publicitario o dinámico para redes."
    />
    <Tarjetadehabilidades
      titulo="Conocimientos de tendencias"
      descripcion="Me mantengo a la vanguardia de la industria audiovisual, monitoreando constantemente las tendencias y técnicas actuales de edición en redes sociales. "
    />
    <Tarjetadehabilidades
      titulo="Edicion al detalle"
      descripcion="Trabajo con un enfoque meticuloso y de alta precisión, revisando minuciosamente cada segundo del metraje para corregir pequeños errores o inconsistencias. "
    />
    <Tarjetadehabilidades
      titulo="Gestión del tiempo y cumplimiento de plazos"
      descripcion="Gestiono cada proyecto con máxima organización, garantizando un flujo de trabajo eficiente que asegura la entrega puntual de tus videos."
    />
  </div>
</section>

<section class="flex gap-10 py-20 px-8 border border-neutral-600/40">
  <div>
    <p class="text-4xl font-bold">SOFTWARE</p>
    <p class="py-7">
      Domino absoluto de las herramientas estandar que definen el cine
      contemporaneo.
    </p>
  </div>
  <div class="flex gap-22 px-18 py-6">
    <p class="">CAPCUT PRO</p>
    <p>PREMIERE PRO</p>
    <p>AFTER EFFECTS</p>
  </div>
</section>

<section class="flex">
  <div class="flex-1">
    <p>Trabajos relacionados</p>

    <video controls class="h-300 w-full object-cover">
      <source src="/video-page.mp4" />
    </video>
  </div>

  <div class="flex-1">
    <div>
      <a href="/work">ver archivo completo</a>
      <p>Ritmo cinematico</p>
      <p>una exploracion de movimientos y magia</p>
      <button>
        <Icon icon="mdi:play" width={32} height={32} />
      </button>
    </div>
  </div>
</section>
