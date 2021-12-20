<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.tema2-background

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Sistema de producción pecuario

    .row.justify-content-center.mb-5
      .col-lg-5
        .contenedor-imagen.position-bottom-left.color-primario.mb-4.mb-lg-0
          figure
            img(src="@/assets/curso/tema2-img1.jpg")
      .col-lg-7
        p.mb-4 De acuerdo con la FAO (Organización de las Naciones Unidas para la Alimentación y la Agricultura) los animales destinados a la producción pecuaria brindan diversos servicios y bienes al ser humano, como los son la leche, la carne, los huevos, las pieles, las plumas, las fibras, tracción y estiércol, entre otras, empero cumplen, además, otras funciones de carácter económico y social en las diferentes comunidades.
        .row.justify-content-center
          .col-8.col-md-3.col-lg-2
            figure.mb-4.mb-lg-0
              img(src="@/assets/curso/tema2-img2.svg")
          .col-md-9
            p.mb-0 Por ejemplo, un animal como la vaca es muy comercial y aprovechable por los seres humanos tal como se ve a continuación, tanto así que muchas personas dicen que de la vaca no se desperdicia nada:

    .titulo-quinto.color-acento-contenido.mb-4
      h4(style="color: #78B632") Ganado Aprovechable

    .row.justify-content-center.mb-5
      .col-md-10
        figure
          img(src="@/assets/curso/tema2-img3.jpg")

    .row.cajon.color-primario.p-4.mb-5.justify-content-center.align-items-center
      .col-3.col-md-3.col-lg-1.mb-4.mb-lg-0
        figure.px-3
          img(src="@/assets/curso/tema2-img4.svg")
      .col-12.col-md-9.col-lg-11
        p.mb-0 Estas producciones tienen diferentes fines entre los que se destacan principalmente las ventas regionales o el autoconsumo o producción a mayor escala para proveer los mercados a nivel nacional e internacional. Así, el objeto, el tamaño y el fin de la producción es lo que se denomina sistema productivo, es así como los animales rumiantes como el ganado bovino, caprino y ovino, tiende a depender directamente de la tierra. Por tanto, sus sistemas de producción están determinados en gran medida por la agroecología y el uso de la tierra. Los sistemas de producción de especies monogástricas como los cerdos y los pollos dependen más de la demanda de los consumidores y del nivel de inversión de capital.

    #t_2_1.titulo-segundo.color-secundario
      h2 2.1  Clases y características

    p.mb-5 Existen diferentes tipos de sistemas productivos de acuerdo con la especie pecuaria que se tenga en producción, debido a que está relacionado con los aspectos etológicos, sanitarios, técnicos y de bienestar para cada una de ellas. En Latinoamérica los principales sistemas de producción que se manejan son los extensivos, intensivos y trashumantes:

    div.titulo-tercero.title-nuevo.mt-5.mb-4
      span Sistemas Pecuarios

    p.mb-4 Los sistemas más comunes . . .

    h3.titulo-tercero.text-center El desempeño animal cambia en cada sistema

    .row.justify-content-center
      .col.col-md-6.col-lg-4.mb-5.mb-lg-0
        figure
          img(src="@/assets/curso/tema2-img5.svg")
        p.mt-3.ms-5 Productores pequeños y medianos muy próximos al ecosistema natural abierto. Los animales buscan su propio alimento y se mueven libres
      .col.col-md-6.col-lg-4.mb-5.mb-lg-0
        figure
          img(src="@/assets/curso/tema2-img6.svg")
        p.mt-3.ms-5 Animales estabulados la mayor parte de su vida están en encierro. Se debe suministrar todo a los animales en los tiempos y espacios que el operario disponga.
          br
          br
          strong El animal depende del operario.
      .col.col-md-6.col-lg-4
        figure
          img(src="@/assets/curso/tema2-img7.svg")
        p.mt-3.ms-5 Los animales se mueven de un lugar a otro de acuerdo a las condiciones medio ambientales y los recursos disponibles en la zona, también se conoce como producción nómada.
          br
          br
          strong No todos los animales se benefician con este tipo de sistema trashumante.

    #t_2_2.titulo-segundo.color-secundario
      h2 2.2  Componentes

    p.mb-5 Los sistemas productivos cuentan con diferentes componentes de acuerdo con la producción específica y el tipo de producción, estos componentes deben ser como piezas de un engranaje de una maquinaria que necesitan trabajar todos juntos secuencialmente para que todo funcione.

    .titulo-sexto.color-acento-contenido
      h5 Figura 2
      span Componentes de un sistema productivo

    .row.justify-content-center.mb-5
      .col-11
        figure
          img(src="@/assets/curso/tema2-img8.svg")

    .contenedor-especial.row.align-items-center.pe-5.py-2.mb-4
      .col-lg-5
        figure.px-5
          img(src="@/assets/curso/tema2-img10.png")
      .col-lg-7
        p.mb-0 Podría decirse que los sistemas productivos están compuestos por elementos como los tipos de animales (razas, edades, líneas), alimento, insumos pecuarios, equipos, infraestructura, predio, personal, entre otros, en donde procesos como el manejo sanitario, alimenticio, reproductivo, ambiental, de residuos y del producto final, deben ser incorporados, así como el manejo hasta llegar al consumidor final, garantizando la calidad e inocuidad de los productos de origen animal.


    .row.justify-content-center
      .col-lg-9
        .tarjeta.color-primario--claro.p-4.mb-5.px-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2-img11.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 Para reforzar el tema se recomienda ver el material audiovisual Sistemas de producción animal que se encuentra disponible en el material complementario o a través del siguiente enlace:
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(href="https://www.youtube.com/watch?v=5VDR_vtHRLQ" target="_blank")
                    span Ver video
                    i.fas.fa-file-download

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
