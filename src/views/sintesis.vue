<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-3 El componente formativo Aditivos: usos y aplicaciones en la industria alimentaria, aborda las generalidades de los aditivos alimentarios, su origen, tipos y clasificación funcional, así como sus usos y aplicaciones en la industria alimentaria, con énfasis en colorantes, conservantes, antioxidantes, edulcorantes, estabilizantes, reguladores de pH y potenciadores de sabor. Se analizan sus funciones tecnológicas y su impacto sobre la calidad, la estabilidad fisicoquímica y las características organolépticas de los alimentos procesados.
    p.mb-3 Asimismo, se desarrolla la nomenclatura, el etiquetado y la normatividad vigente, estableciendo la relación entre el uso de aditivos y el análisis fisicoquímico como herramienta de control de calidad e inocuidad. El componente integra el manejo y la conversión de unidades de medida como competencia transversal, fortaleciendo la correcta dosificación y el cumplimiento de la Ingesta Diaria Admisible (IDA), en coherencia con los estándares técnicos del sector alimentario.
    .row.justify-content-center
      .col-lg-12.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis/sintesis.svg", alt="El componente formativo Aditivos: usos y aplicaciones en la industria alimentaria, aborda las generalidades de los aditivos alimentarios, su origen, tipos y clasificación funcional, así como sus usos y aplicaciones en la industria alimentaria, con énfasis en colorantes, conservantes, antioxidantes, edulcorantes, estabilizantes, reguladores de pH y potenciadores de sabor. Se analizan sus funciones tecnológicas y su impacto sobre la calidad, la estabilidad fisicoquímica y las características organolépticas de los alimentos procesados. Asimismo, se desarrolla la nomenclatura, el etiquetado y la normatividad vigente, estableciendo la relación entre el uso de aditivos y el análisis fisicoquímico como herramienta de control de calidad e inocuidad. El componente integra el manejo y la conversión de unidades de medida como competencia transversal, fortaleciendo la correcta dosificación y el cumplimiento de la Ingesta Diaria Admisible (IDA), en coherencia con los estándares técnicos del sector alimentario.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
