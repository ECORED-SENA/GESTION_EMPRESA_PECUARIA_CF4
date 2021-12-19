<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.tema1-background

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Producción pecuaria

    .row.justify-content-center.mb-5
      .col-lg-7
        p.mb-0 Este es el término que se la da a la vinculación de diversos factores relevantes para el proceso productivo pecuario, estos procesos son los sistemas de producción, las buenas prácticas ganaderas, el bienestar, el reconocimiento de los factores de riesgo sanitario, la enfermedades de notificación especial, la bioseguridad, el manejo de la alimentación, nutrición y el aprovechamiento de los datos que se generan en cada uno de los pasos del proceso productivo, entre otros; lo anterior hace necesario un punto de encuentro de todos estos procesos en un solo cronograma de trabajo y en una sola consecución de recursos que permitan realizar la misión de la empresa pecuaria en general buscando llevar organizadamente la producción logrando más eficiente y productividad, en ese orden de ideas trabaja la producción pecuaria.
          br
          br
          | Dentro de las características más reconocidas del sector pecuario se pueden citar las siguientes:
      .col-lg-5
        .contenedor-imagen.color-primario.position-top-right
          figure
            img(src="@/assets/curso/tema1-img1.jpg")

    .row.mb-5
      .col-12.col-md-6.col-lg.d-flex.mb-5.mb-lg-0
        figure
          img(src="@/assets/curso/tema1-img2.svg")
      .col-12.col-md-6.col-lg.d-flex.mb-5.mb-lg-0
        figure
          img(src="@/assets/curso/tema1-img3.svg")
      .col-12.col-md-6.col-lg.d-flex.mb-5.mb-lg-0
        figure
          img(src="@/assets/curso/tema1-img4.svg")
      .col-12.col-md-6.col-lg.d-flex.mb-5.mb-lg-0
        figure
          img(src="@/assets/curso/tema1-img5.svg")
      .col-12.col-md-6.col-lg.d-flex.mb-5.mb-lg-0
        figure
          img(src="@/assets/curso/tema1-img6.svg")

    p.mb-5 Entonces, se puede decir que las actividades más destacables y populares dentro de este sector son las producciones, bovinas, porcinas, ovinas y avícolas.
      br
      br
      | Actividades destacadas de la producción pecuaria:

    .row.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1-img7.svg')
          .tarjeta.color-primario.w-100
            .text-white.p-4
              h2.text-center Bovina
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1-img8.svg')
          .tarjeta.color-primario.w-100
            .text-white.p-4
              h2.text-center Porcina
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1-img9.svg')
          .tarjeta.color-primario.w-100
            .text-white.p-4
              h2.text-center Ovina
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1-img10.svg')
          .tarjeta.color-primario.w-100
            .text-white.p-4
              h2.text-center Avícola

</template>

<script>
export default {
  name: 'Tema1',
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
