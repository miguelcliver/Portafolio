<script>
  import Tarjetadehabilidades from "$lib/components/Tarjetadehabilidades.svelte";

</script>
<section>
  <p>Editor de video profesional</p>
  <div>
    <p>Michael Montañez</p>
    <p>escrito de algo</p>
  </div>
  <img src="/unnamed.png" alt="" />
</section>

<section>
  <div>
    <p>Mi historia</p>
  </div>
  <div>
    <p>texto1</p>
    <p>texto2</p>
    <div>
      <div>
        <p>textoverde1</p>
        <p>textoblanco1</p>
      </div>
      <div>
        <p>textoverde2</p>
        <p>textoblanco2</p>
      </div>
    </div>
  </div>
</section>

<section>
    <div>
        <p>HABILIDADES</p>
    </div>
    <div>
        <Tarjetadehabilidades titulo="Soporte tecnico" descripcion="servicio de asistencia que ayuda a los usuarios o empresas a resolver problemas con sus equipos, programas o sistemas tecnológicos" />
        <Tarjetadehabilidades titulo="diseño sonoro" descripcion="El diseño sonoro es la disciplina artística y técnica que consiste en crear, adquirir, manipular o generar elementos de audio para un medio específico, como el cine, la televisión, los videojuegos"/>
        <Tarjetadehabilidades titulo="edicion tecnica" descripcion="La edición técnica es el proceso de revisar, corregir y optimizar textos de carácter especializado (científicos, tecnológicos, financieros o académicos) antes de su publicación."/>
        <Tarjetadehabilidades titulo="Dominio de software de edición"descripcion="Manejo avanzado de programas profesionales como Adobe Premiere Pro, Final Cut Pro o DaVinci Resolve para cortar, estructurar y exportar material visual de forma óptima."/>
        <Tarjetadehabilidades titulo="Narrativa visual"descripcion="Capacidad para seleccionar las mejores tomas y unirlas con el ritmo, la música y la coherencia necesarios para contar una historia atractiva que mantenga el interés del espectador."/>

    </div>
</section>
