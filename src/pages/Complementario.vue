<template>
  <div class="curso-main-container complementario">
    <BannerInterno
      icono="far fa-folder-open"
      titulo="Material complementario"
    ></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="table-responsive">
        <table>
          <thead>
            <tr>
              <th colspan="3" scope="col">Tema</th>
              <th colspan="5" scope="col">Referencia APA del material</th>
              <th colspan="2" scope="col">Tipo</th>
              <th colspan="2" scope="col">Enlace</th>
            </tr>
          </thead>
          <tbody>
            <tr
              v-for="(item, index) in computedData"
              :key="'complementario-' + index"
            >
              <td
                class="text-start"
                colspan="3"
                scope="row"
                v-html="item.tema"
              ></td>
              <td
                class="text-start"
                colspan="5"
                scope="row"
                v-html="item.referencia"
              ></td>
              <td colspan="2" v-html="item.tipo"></td>
              <td colspan="2">
                <div class="complementario__enlaces">
                  <a
                    v-for="(link, linkIndex) of item.link"
                    :key="linkIndex"
                    class="complementario__btn"
                    :href="link"
                    target="_blank"
                    ><i class="fas fa-external-link-alt"></i
                  ></a>
                </div>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'MaterialComplementario',
  computed: {
    complementarioData() {
      return [
        {
          tema: 'Automatismos Eléctricos, agricultura 4.0.',
          referencia:
            'español), E. (en [@euronewses]. (n.d.). La agricultura 4.0: tecnología sustentable para afrontar el futuro. [Video]. Youtube.',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=WccvffGgDms&t=313s',
        },
        {
          tema: 'Automatismos Eléctricos',
          referencia: 'Smart agriculture. (n.d.). [Documento PDF] Semtech.com.',
          tipo: 'Pagina electrónica, Documento PDF',
          link:
            'https://www.semtech.com/lora/lora-applications/smart-agriculture',
        },
        {
          tema: 'Introducción a la Agricultura de Precisión',
          referencia:
            'Universidad Nacional Agraria - Nicaragua. (2017). ¿Qué es Agricultura de Precisión? [Video]. YouTube.',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=3CHz9Ul6RFQ',
        },
        {
          tema: 'Aplicaciones Prácticas de la Agricultura de Precisió ',
          referencia:
            'Universidad EARTH [@EARTH_Uni]. (n.d.). Ideas EARTH | Webinar: Agricultura de precisión y su aplicación práctica. [Video]. Youtube.',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=V0XpvRE7M1s',
        },
        {
          tema: 'Software de Uso Libre para Agricultura de Precisión',
          referencia: 'FastMapping. (n.d.). Edu.ar.',
          tipo: 'Software web',
          link: 'https://fastmapping.psi.unc.edu.ar/',
        },
        {
          tema: 'Agricultura de Precisión',
          referencia: 'Edu.co. (n.d.). [Documento PDF].',
          tipo: 'Documento',
          link:
            'https://www.ucundinamarca.edu.co/unidadapoyoacademico/images/2021/agrointeligente/USO_DE_LAS_HERRAMIENTAS.pdf',
        },
        {
          tema: 'Plataforma para Agricultura de Precisió',
          referencia:
            'Sgargi, C. (2024, junio 11). Agricolus - La plataforma para la agricultura de precisión. Agricolus; Agricolus srl.',
          tipo: 'Pagina Web',
          link: 'https://www.agricolus.com/es/',
        },
      ]
    },
    computedData() {
      const data = this.complementarioData
      return data.map(item => {
        let nuevoLink = []
        if (item.link) {
          if (typeof item.link === 'string') {
            nuevoLink.push(item.link)
          } else {
            nuevoLink = item.link
          }
        } else if (item.descarga) {
          if (typeof item.descarga === 'string') {
            nuevoLink.push(this.obtenerLink(item.descarga))
          } else {
            item.descarga.forEach(link => {
              nuevoLink.push(this.obtenerLink(link))
            })
          }
        }
        return {
          ...item,
          link: nuevoLink,
        }
      })
    },
  },
}
</script>

<style lang="sass">
.complementario
  &__enlaces
    display: flex
    justify-content: center
    flex-wrap: wrap
    a
      margin: 0 5px
  &__btn
    font-size: 1.5em
    line-height: 1em
table
  width: calc(100% - 1px)
  min-width: 800px
  thead
    background-color: $color-sistema-e
    th
      border-color: $color-sistema-e
  th, td
    padding: 25px 20px
    text-align: center
</style>
