<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5 bg2">
      <div class="titulo-principal color-acento-contenido">
        <div class="titulo-principal__numero"><span>2</span></div>
        <h1>Fundamentos de los sistemas de información</h1>
      </div>
      <div class="row justify-content-center mb-5">
        <div class="col-lg-4 mb-lg-0 mb-3">
          <div class="tarjeta p-4 h-100" style="background-color: #B0C4D7">
            <p class="mb-0">
              Los Sistemas de Información Geográfica (SIG) y el Sistema de
              Posicionamiento Global (GPS) son pilares fundamentales en la
              implementación de sistemas automatizados para el monitoreo y
              gestión de labores agrícolas. Estas herramientas permiten analizar
              y gestionar grandes volúmenes de datos georreferenciados, lo que
              es valioso para la agricultura de precisión. Este capítulo
              proporciona una fundamentación teórica sólida sobre estos
              sistemas, explorando sus componentes, funcionamiento y
              aplicaciones en el ámbito agropecuario.
            </p>
          </div>
        </div>
        <div class="col-lg-4 col-7 mb-lg-0 mb-3">
          <img src="@/assets/curso/temas/11.png" alt="" />
        </div>
        <div class="col-lg-4 mb-lg-0 mb-3">
          <div class="tarjeta p-4 h-100" style="background-color: #D7E1EB">
            <img
              class="mb-3"
              src="@/assets/curso/temas/12.svg"
              alt=""
              style="width: 85px"
            />
            <p class="mb-0">
              Así mismo, se incluye una revisión de los sensores IoT, que se
              integran con SIG y GPS para monitorear variables agrícolas en
              tiempo real. Esta combinación tecnológica permite a los
              agricultores tomar decisiones basadas en datos precisos,
              optimizando los recursos y mejorando la sostenibilidad del sistema
              productivo.
            </p>
          </div>
        </div>
      </div>
      <Separador></Separador>
      <div
        id="t_2_1"
        class="titulo-segundo color-acento-contenido"
        data-aos="fade-right"
      >
        <h2>2.1 Sistemas de Información Geográfica (SIG)</h2>
      </div>
      <div class="row align-items-center">
        <div class="col-lg-auto">
          <img
            class="mx-auto"
            src="@/assets/curso/temas/13.svg"
            style="max-width: 90px"
          />
        </div>
        <div class="col-lg">
          <p class="mb-0">
            En la agricultura moderna, el manejo eficiente de grandes volúmenes
            de datos espaciales es clave para la toma de decisiones precisas y
            oportunas. Los Sistemas de Información Geográfica (SIG) se han
            consolidado como una herramienta fundamental para integrar y
            analizar información georreferenciada, permitiendo visualizar y
            comprender patrones espaciales complejos. A través de mapas, modelos
            y análisis espaciales, los SIG facilitan la identificación de áreas
            críticas en las unidades productivas, optimizando así las
            operaciones agrícolas y contribuyendo a una gestión más sostenible.
          </p>
        </div>
      </div>
      <div class="row justify-content-center mb-5">
        <div class="col-lg-8 mb-lg-0 mb-3">
          <p class="mb-4">
            El GPS es un sistema de navegación por satélite que permite
            determinar la posición geográfica precisa de una persona, animal o
            cosa en cualquier lugar del mundo. Fue desarrollado originalmente
            por el Departamento de Defensa de los Estados Unidos y es operado
            por una constelación de al menos 24 satélites en órbita terrestre.
          </p>
          <div class="p-4" style="background-color:  #98E2EC">
            <p class="mb-0">
              El GPS funciona mediante la recepción de señales de radio emitidas
              por los satélites, que contienen información sobre ubicación y el
              tiempo. Para que se pueda generar la ubicación, deben al menos
              encontrarse la señal emitida por cuatro satélites los cuales deben
              estar visibles desde el receptor para calcular coordenadas
              tridimensionales, que corresponden a la latitud, la longitud y la
              altitud, o a su equivalente de geolocalización.
            </p>
          </div>
        </div>
        <div class="col-lg-4 col-7">
          <img src="@/assets/curso/temas/14.png" alt="" />
        </div>
      </div>
      <div class="row justify-content-center mb-5">
        <div class="col-lg-4 col-7 mb-lg-0 mb-3">
          <img src="@/assets/curso/temas/15.png" alt="" />
        </div>
        <div class="col-lg-8">
          <p class="mb-4">Sus principales usos incluyen:</p>
          <ul class="lista-ul--color">
            <li class="d-flex mb-1">
              <i class="fas fa-check-circle"></i>
              <p class="mb-0">
                Navegación en medios de transporte terrestre, marítimo y aéreo.
              </p>
            </li>
            <li class="d-flex mb-1">
              <i class="fas fa-check-circle"></i>
              <p class="mb-0">
                Geolocalización en dispositivos móviles y aplicaciones de mapas.
              </p>
            </li>
            <li class="d-flex mb-1">
              <i class="fas fa-check-circle"></i>
              <p class="mb-0">
                Monitoreo de flotas, de actividades deportivas y útil para
                movilizarse y para el rescate.
              </p>
            </li>
            <li class="d-flex mb-1">
              <i class="fas fa-check-circle"></i>
              <p class="mb-0">
                Agricultura de precisión y levantamientos topográficos.
              </p>
            </li>
          </ul>
          <p class="mb-0">
            Es un sistema confiable, de alta precisión, y está disponible
            globalmente de forma gratuita para el uso civil, existiendo otros
            sistemas de navegación como el Glonass, el Beidou, y el sistema
            Galileo.
          </p>
        </div>
      </div>
      <div class="bg-slyder mn p-5 mb-5">
        <div class="tarjeta bg-white p-5">
          <CarouselRED tipo="b">
            <div class="row justify-content-center">
              <div class="col-lg-6 mb-4 mb-md-0">
                <h4>Componentes de un GPS</h4>
                <ul class="lista-ul--color">
                  <li class="d-flex mb-1">
                    <i class="fas fa-check-circle"></i>
                    <p class="mb-0">
                      <b>Datos vectoriales:</b> representan elementos
                      geográficos como puntos, líneas y polígonos (e.g., pozos,
                      caminos y parcelas).
                    </p>
                  </li>
                  <li class="d-flex mb-1">
                    <i class="fas fa-check-circle"></i>
                    <p class="mb-0">
                      <b>Datos ráster:</b> imágenes o mapas compuestos por una
                      matriz de píxeles, que representan variables continuas
                      como elevación o humedad del suelo.
                    </p>
                  </li>
                  <li class="d-flex mb-1">
                    <i class="fas fa-check-circle"></i>
                    <p class="mb-0">
                      <b>Bases de datos espaciales:</b> almacenan información
                      tabular relacionada con los elementos geográficos.
                    </p>
                  </li>
                  <li class="d-flex mb-1">
                    <i class="fas fa-check-circle"></i>
                    <p class="mb-0">
                      <b><em>Software:</em></b> herramientas como QGIS, ArcGIS o
                      similares que permiten la manipulación y análisis de datos
                      geoespaciales.
                    </p>
                  </li>
                </ul>
              </div>
              <div class="col-lg-5 col-7">
                <figure>
                  <img
                    src="@/assets/curso/temas/16.png"
                    alt="Texto que describa la imagen"
                  />
                </figure>
              </div>
            </div>
            <div class="row justify-content-center">
              <div class="col-lg-6 mb-4 mb-md-0">
                <h4>Aplicaciones en agricultura</h4>
                <p>
                  Los SIG son cada vez más importantes para la agricultura de
                  precisión, permitiendo:
                </p>
                <ul class="lista-ul--color">
                  <li class="d-flex mb-1">
                    <i class="fas fa-check-circle"></i>
                    <p class="mb-0">
                      <b>Mapeo de rendimiento:</b> identificación de áreas con
                      diferentes niveles de productividad.
                    </p>
                  </li>
                  <li class="d-flex mb-1">
                    <i class="fas fa-check-circle"></i>
                    <p class="mb-0">
                      <b>Análisis de suelos:</b> mapas de fertilidad y
                      propiedades físicas del suelo.
                    </p>
                  </li>
                  <li class="d-flex mb-1">
                    <i class="fas fa-check-circle"></i>
                    <p class="mb-0">
                      <b>Monitoreo de plagas y enfermedades:</b> detección y
                      seguimiento geoespacial de brotes.
                    </p>
                  </li>
                </ul>
              </div>
              <div class="col-lg-5 col-7">
                <figure>
                  <img
                    src="@/assets/curso/temas/17.png"
                    alt="Texto que describa la imagen"
                  />
                </figure>
              </div>
            </div>
          </CarouselRED>
        </div>
      </div>
      <Separador></Separador>
      <div
        id="t_2_2"
        class="titulo-segundo color-acento-contenido"
        data-aos="fade-right"
      >
        <h2>2.2 Sistema de Posicionamiento Global (GPS)</h2>
      </div>
      <div class="row justify-content-center mb-5">
        <div class="col-lg-8 mb-lg-0 mb-3">
          <p class="mb-4">
            El Sistema de Posicionamiento Global (GPS) es una tecnología que se
            usa para el monitoreo y gestión de labores agrícolas. Su capacidad
            para proporcionar datos de localización precisos en tiempo real
            permite a los agricultores mejorar la eficiencia de tareas como la
            delimitación de parcelas, la planificación de rutas de maquinaria y
            el muestreo georreferenciado. Esta herramienta se integra
            perfectamente con otros sistemas tecnológicos, como los SIG, para
            generar análisis geoespaciales más detallados y precisos.
          </p>
          <AccordionRED class="mb-5" clase-tarjeta="tarjeta tarjeta--azul">
            <div titulo="Fundamentos del GPS">
              <p class="mb-0">
                El Sistema de Posicionamiento Global (GPS) utiliza una red de
                satélites para determinar la ubicación exacta de un objeto en la
                superficie terrestre. Su precisión y capacidad para trabajar en
                tiempo real lo hacen invaluable en el monitoreo agrícola.
              </p>
            </div>
            <div titulo="Componentes del GPS">
              <ul class="lista-ul--color">
                <li class="d-flex mb-1">
                  <i class="fas fa-check-circle"></i>
                  <p class="mb-0">
                    <b>Segmento espacial:</b> satélites que emiten señales.
                  </p>
                </li>
                <li class="d-flex mb-1">
                  <i class="fas fa-check-circle"></i>
                  <p class="mb-0">
                    <b>Segmento de control:</b> estaciones en tierra que
                    supervisan y ajustan las órbitas satelitales.
                  </p>
                </li>
                <li class="d-flex mb-1">
                  <i class="fas fa-check-circle"></i>
                  <p class="mb-0">
                    <b>Segmento del usuario:</b> receptores GPS que capturan
                    señales y calculan la posición geográfica.
                  </p>
                </li>
              </ul>
            </div>
            <div titulo="Aplicaciones en agricultura">
              <ul class="lista-ul--color">
                <li class="d-flex mb-1">
                  <i class="fas fa-check-circle"></i>
                  <p class="mb-0">
                    <b>Delimitación de parcelas:</b> precisión en la división y
                    gestión de áreas de cultivo.
                  </p>
                </li>
                <li class="d-flex mb-1">
                  <i class="fas fa-check-circle"></i>
                  <p class="mb-0">
                    <b>Rutas de maquinaria agrícola:</b> optimización de
                    trayectorias para labores como siembra y cosecha.
                  </p>
                </li>
                <li class="d-flex mb-1">
                  <i class="fas fa-check-circle"></i>
                  <p class="mb-0">
                    <b>Muestreo georreferenciado:</b> toma de muestras de suelo
                    o plantas en ubicaciones específicas.
                  </p>
                </li>
              </ul>
            </div>
          </AccordionRED>
        </div>
        <div class="col-lg-4 col-7">
          <img src="@/assets/curso/temas/18.png" alt="" />
        </div>
      </div>
      <Separador></Separador>
      <div
        id="t_2_3"
        class="titulo-segundo color-acento-contenido"
        data-aos="fade-right"
      >
        <h2>2.3 Sensores IoT en la agricultura</h2>
      </div>
      <div class="row justify-content-center mb-5">
        <div class="col-lg-5 col-7 mb-lg-0 mb-3">
          <img src="@/assets/curso/temas/19.png" alt="" />
        </div>
        <div class="col-lg-7">
          <p class="mb-4">
            La revolución tecnológica en la agricultura no estaría completa sin
            la incorporación de los sensores IoT (Internet de las Cosas). Estos
            dispositivos recopilan datos en tiempo real sobre diversas variables
            agrícolas, como la humedad del suelo, la temperatura y los niveles
            de nutrientes, y los transmiten de manera automática para su
            análisis y procesamiento. La integración de sensores IoT con SIG y
            GPS permite una supervisión continua y precisa de las condiciones de
            campo, facilitando la automatización de decisiones críticas como el
            riego o la fertilización.
          </p>
          <AccordionRED class="mb-5" clase-tarjeta="tarjeta tarjeta--azul">
            <div titulo="Concepto y tipos de sensores IoT">
              <p class="mb-0">
                Los sensores IoT son dispositivos que recopilan datos
                específicos en campo y los transmiten en tiempo real a través de
                redes inalámbricas. En el ámbito agrícola, estos sensores
                permiten medir parámetros críticos como la humedad del suelo, la
                temperatura, la salinidad y los niveles de nutrientes.
              </p>
            </div>
            <div titulo="Tipos de sensores utilizados">
              <ul class="lista-ul--color">
                <li class="d-flex mb-1">
                  <i class="fas fa-check-circle"></i>
                  <p class="mb-0">
                    <b>Sensores de humedad del suelo:</b> miden el contenido de
                    agua en el suelo, facilitando la optimización del riego.
                  </p>
                </li>
                <li class="d-flex mb-1">
                  <i class="fas fa-check-circle"></i>
                  <p class="mb-0">
                    <b>Sensores climáticos:</b> registran temperatura, humedad
                    relativa y velocidad del viento.
                  </p>
                </li>
                <li class="d-flex mb-1">
                  <i class="fas fa-check-circle"></i>
                  <p class="mb-0">
                    <b>Sensores de nutrientes:</b> detectan niveles de
                    nitrógeno, fósforo y potasio en el suelo.
                  </p>
                </li>
              </ul>
            </div>
          </AccordionRED>
        </div>
      </div>
      <Separador> </Separador>
      <div
        id="t_2_4"
        class="titulo-segundo color-acento-contenido"
        data-aos="fade-right"
      >
        <h2>2.4 Integración con SIG y GPS</h2>
      </div>
      <div class="row justify-content-center mb-5">
        <div class="col-lg-3 col-7 mb-lg-0 mb-3">
          <img src="@/assets/curso/temas/20.png" alt="" />
        </div>
        <div class="col-lg-9">
          <p class="mb-4">
            Los datos recolectados por sensores IoT se integran en tiempo real
            con plataformas SIG y GPS, lo que permite:
          </p>
          <ul class="lista-ul--color">
            <li class="d-flex mb-1">
              <i class="fas fa-check-circle"></i>
              <p class="mb-0">
                <b>Monitoreo continuo:</b> supervisión constante de las
                condiciones del cultivo.
              </p>
            </li>
            <li class="d-flex mb-1">
              <i class="fas fa-check-circle"></i>
              <p class="mb-0">
                <b>Toma de decisiones automatizada:</b> activación de sistemas
                como riego o fertilización basados en datos específicos.
              </p>
            </li>
            <li class="d-flex mb-1">
              <i class="fas fa-check-circle"></i>
              <p class="mb-0">
                <b>Visualización espacial:</b> representación de variables en
                mapas para identificar patrones y áreas críticas.
              </p>
            </li>
          </ul>
        </div>
      </div>
      <div class="titulo-sexto color-acento-contenido" data-aos="fade-right">
        <h5>Figura 2.</h5>
        <span>Resumen fundamentos de los sistemas de información</span>
      </div>
      <img
        src="@/assets/curso/temas/21.svg"
        alt="La Figura 2 se denomina «Resumen Fundamentos de los sistemas de información» ilustra los fundamentos de los sistemas de información en la agricultura, destacando el uso de los Sistemas de Información Geográfica (SIG) y el Sistema de Posicionamiento Global (GPS). Se abordan sus componentes, funciones y aplicaciones en el monitoreo de cultivos, planificación de riego y control de plagas. También se resalta la integración de sensores IoT con estas tecnologías."
      />
      <figcaption>Fuente: OIT, 2024.</figcaption>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
