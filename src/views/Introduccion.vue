<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .d-flex.flex-wrap.align-items-end.fondo-slider(
      :style="{'background-image': `url(${require('@/assets/curso/intro/intro.svg')})`, 'margin-bottom': '-3rem', 'padding-bottom': '3rem'}"
    )
      .col-lg-9.pe-lg-3.order-2.order-lg-1
        p.mb-4 En el presente componente se abordan los temas: activos financieros, pasivos financieros, instrumentos de patrimonio y la normatividad vigente aplicable al presente tema. Los instrumentos financieros son contratos que dan lugar, simultáneamente, a un activo financiero en una entidad y a un pasivo financiero o a un instrumento de patrimonio en otra entidad, lo que permite concretar todos estos conceptos en el momento de reconocer, medir y revelar de manera correcta los diferentes títulos que se comercian a diario en el mercado de capitales y que forman parte del día a día de cualquier empresa en sus procesos de maximizar la rentabilidad de sus activos y de financiación de su negocio.
        .d-flex.flex-wrap.align-items-center(style="background-color: #FEEAD4")
          img.col-12.col-lg-5(src="@/assets/curso/intro/img-2.jpg").m-auto
          p.mb-0.p-3.p-xxl-5.col #[b Nota aclaratoria:] las tablas que se toman como referencia en los ejemplos de cada uno de los temas desarrollados, elaboradas mediante el programa Excel, son derivadas de estos ejercicios, la elaboración es propia del autor del presente componente, por lo tanto, no se numeran y no se establece un nombre específico.
      .col-lg-3.d-flex.m-auto.mb-4.mb-lg-0.order-1.order-lg-2
        img.m-auto(src="@/assets/curso/intro/img-1.png" style="max-width: 295px")
</template>

<script>
export default {
  name: 'Introduccion',
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
