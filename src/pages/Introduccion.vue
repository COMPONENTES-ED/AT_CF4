<template>
  <div class="curso-main-container introduccion">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido">
        <div class="titulo-principal__numero">
          <span><i class="fas fa-info"></i></span>
        </div>
        <h1>Introducción</h1>
      </div>
      <div class="row justify-content-center mb-4">
        <div class="col-lg-9 mb-lg-0 mb-3">
          <p class="mb-4">
            En un contexto global donde la sostenibilidad y la eficiencia
            productiva son cada vez más relevantes, el sector agropecuario
            enfrenta el reto de optimizar el uso de sus recursos mientras
            maximiza el rendimiento. Para lograrlo, la integración de
            tecnologías avanzadas se ha convertido en una necesidad. Este
            componente, Sistemas automatizados para el monitoreo y gestión de
            labores agrícolas, proporciona al aprendiz las bases teóricas y
            prácticas necesarias para implementar soluciones tecnológicas que
            permitan un monitoreo eficiente y una toma de decisiones basada en
            datos.
          </p>
          <div class="row justify-content-center">
            <div class="col-lg-5 col-7 mb-lg-0 mb-3">
              <img src="@/assets/curso/temas/1.png" alt="" />
            </div>
            <div class="col-lg-7">
              <div class="p-4 h-100" style="background-color: #C8E2AA">
                <p class="mb-0">
                  El monitoreo de labores agrícolas se sustenta en herramientas
                  como los Sistemas de Información Geográfica (SIG), el Sistema
                  de Posicionamiento Global (GPS) y sensores IoT. Estas
                  tecnologías posibilitan la recopilación, análisis y
                  visualización de datos geoespaciales en tiempo real,
                  fundamentales para identificar la variabilidad espacial y
                  temporal en las unidades productivas. A través de este
                  conocimiento, es posible diseñar estrategias específicas para
                  cada zona del cultivo, optimizando el uso de insumos como
                  agua, fertilizantes y pesticidas.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 d-none d-lg-block">
          <img src="@/assets/curso/temas/2.png" alt="" />
        </div>
      </div>
      <p class="mb-4">
        Asimismo, este componente destaca la importancia de sistemas como el
        riego automatizado, que ajustan el suministro de agua en función de las
        condiciones específicas del suelo y del clima. La capacidad de integrar
        estos sistemas con SIG y GPS permite un monitoreo continuo y preciso,
        mejorando la eficiencia de las operaciones agrícolas.
      </p>
      <div class="row justify-content-center mb-5">
        <div class="col-lg-5 col-7 mb-lg-0 mb-3">
          <img src="@/assets/curso/temas/3.png" alt="" />
        </div>
        <div class="col-lg-7">
          <div class="row align-items-center mb-4">
            <div class="col-lg-auto">
              <img
                class="mx-auto"
                src="@/assets/curso/temas/4.svg"
                style="max-width: 90px"
              />
            </div>
            <div class="col-lg">
              <p class="mb-0">
                El aprendiz también explorará el uso de herramientas de
                geoestadística para analizar la variabilidad de los datos y
                generar mapas temáticos que faciliten la toma de decisiones.
                Estas habilidades sirven para implementar prácticas de
                agricultura de precisión, un enfoque que no solo mejora la
                productividad, sino que también reduce el impacto ambiental y
                asegura la sostenibilidad del sistema productivo.
              </p>
            </div>
          </div>
          <p class="mb-0">
            En resumen, este componente prepara al aprendiz para enfrentar los
            desafíos del sector agropecuario moderno, proporcionando las
            competencias necesarias para diseñar, implementar y operar sistemas
            automatizados que promuevan la competitividad y sostenibilidad en el
            campo.
          </p>
        </div>
      </div>
      <p class="mb-4">
        ¡Bienvenido al mundo de los Sistemas automatizados para el monitoreo y
        gestión de labores agrícolas, donde descubrirás cómo integrar tecnología
        avanzada para optimizar recursos, mejorar la productividad y contribuir
        a la sostenibilidad del sector agropecuario!
      </p>
      <figure>
        <div class="video">
          <iframe
            width="560"
            height="315"
            src="https://www.youtube.com/embed/Ej2XbJT65eA?si=nGLOUn2MNcA4aJy2"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen="allowfullscreen"
          ></iframe>
        </div>
      </figure>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
