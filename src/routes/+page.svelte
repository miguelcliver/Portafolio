<script>
  import Software from "$lib/components/Software.svelte";
  import Tarjetadehabilidades from "$lib/components/Tarjetadehabilidades.svelte";
  import Icon from "@iconify/svelte";
</script>

<section class="px-9 py-8">
  <p class="text-8xl font-extrabold uppercase">Editor de video profesional</p>
  <div class="flex justify-end">
    <div>
      <p class="text-[#00E1AB] pb-4">Michael Montañez</p>
      <p class="max-w-xl text-neutral-200">
        Hola, soy Michael. Ayudo a empresas a comunicar sus ideas con videos
        claros, atractivos y de alta calidad. Si buscas un trabajo profesional,
        puntual y adaptado a tus metas, hagamos equipo en tu próximo proyecto.
      </p>
    </div>
  </div>
</section>

<section>
  <div>
    <p>Mi historia</p>
  </div>
  <div>
    <p>
      Empece en el mundo de edicion por curiosidad y por querer aprender algo
      nuevo, percatándome de que es algo q me gusta, empecé a realizar trabajos
      pequeños y ya hace aproximadamente 2 años y 7 meses trabajando
      profesionalmente.
    </p>
    <div>
      <div>
        <p>2014-2018</p>
        <p>inicios en montaje documental y colorimetrica basica</p>
      </div>
      <div>
        <p>2019- presente</p>
        <p>
          especialización en postproducción técnica y narrativa para marcas
          globales
        </p>
      </div>
    </div>
  </div>
</section>

<section>
  <div>
    <p>HABILIDADES</p>
  </div>
  <div>
    <Tarjetadehabilidades
      titulo="Manejo de plataformas"
      descripcion="Domino las herramientas líderes de la industria audiovisual, con un manejo experto de Adobe Premiere Pro y CapCut. Más allá de conocer el software, optimizo cada flujo de trabajo técnico para garantizar una edición limpia y eficiente adaptada al mercado corporativo."
    />
    <Tarjetadehabilidades
      titulo="Adaptacion a diferentes estilos"
      descripcion="Cuento con una alta capacidad de adaptación para moldear el estilo de edición según las necesidades de cada proyecto, ya sea contenido corporativo, publicitario o dinámico para redes. Ajusto con precisión el ritmo, la narrativa y la estética visual para asegurar que el video final conecte de forma natural con tu público objetivo."
    />
    <Tarjetadehabilidades
      titulo="Conocimientos de tendencias"
      descripcion="Me mantengo a la vanguardia de la industria audiovisual, monitoreando constantemente las tendencias y técnicas actuales de edición en redes sociales. Esto me permite aplicar narrativas visuales frescas, ritmos modernos y formatos optimizados que capturan la atención del público de forma inmediata."
    />
    <Tarjetadehabilidades
      titulo="Edicion al detalle"
      descripcion="Trabajo con un enfoque meticuloso y de alta precisión, revisando minuciosamente cada segundo del metraje para corregir pequeños errores o inconsistencias. Me aseguro de que el color, el audio y los cortes de edición queden perfectamente pulidos para entregar un producto final impecable."
    />
    <Tarjetadehabilidades
      titulo="Gestión del tiempo y cumplimiento de plazos"
      descripcion="Gestiono cada proyecto con máxima organización, garantizando un flujo de trabajo eficiente que asegura la entrega puntual de tus videos. Mi compromiso con los plazos de entrega te permite planificar tus campañas con total tranquilidad, sin comprometer jamás la calidad final del material.."
    />
  </div>
</section>

<section>
  <div>
    <p>SOFTWARE</p>
    <p>
      Domino absoluto de las herramientas estandar que definen el cine
      contemporaneo
    </p>
  </div>
  <div>
    <Software numero="01" texto="PREMIERE PRO" />
    <Software numero="02" texto="CAPCUT PRO" />
  </div>
</section>

<section>
  <div>
    <p>Trabajos relacionados</p>
    <img src="/original.webp" alt="" />
  </div>

  <div>
    <a href="/work">ver archivo completo</a>
    <div>
      <p>Ritmo cinematico</p>
      <p>una exploracion de movimientos y magia</p>
      <button>
        <Icon icon="mdi:play" width={32} height={32} />
      </button>
    </div>
  </div>
</section>
