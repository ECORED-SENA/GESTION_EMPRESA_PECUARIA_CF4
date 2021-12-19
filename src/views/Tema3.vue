<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.tema3-background

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Buenas prácticas pecuarias

    p.mb-5 La producción animal y el buen cuidado desde la gestión de la legalidad son fundamentales y por eso se requieren las buenas prácticas, tal como se relata a continuación:

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .row.cajon.color-primario.p-4.mb-5.justify-content-center.align-items-center
      .col-3.col-md-3.col-lg-1.mb-4.mb-lg-0
        figure.px-3
          img(src="@/assets/curso/tema2-img4.svg")
      .col-12.col-md-9.col-lg-11
        p.mb-0 Complementando el contexto se entiende que hay una matriz general de sistemas con jerarquías bien definidas desde la estructura general gubernamental y se evidencia en la siguiente gráfica:


    .titulo-sexto.color-acento-contenido
      h5 Figura 3
      span Instituciones que hacen parte de Sistema de Medidas Sanitarias y Fitosanitarias – MSF de acuerdo con las funciones ICA (2017)

    .row.justify-content-center.mb-5
      .col-md-9
        figure
          img(src="@/assets/curso/tema3-img1.svg")

    #t_3_1.titulo-segundo.color-secundario
      h2 3.1  Interpretación

    .row.justify-content-center.mb-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema3-img2.svg")
      .col-lg-7
        p.mb-4 Las buenas prácticas ganaderas son actividades recomendadas con el propósito de disminuir riesgos físicos, químicos y biológicos en la producción primaria de alimentos de origen animal, promoviendo la sanidad, el bienestar animal y la protección del medio ambiente, pudiendo aplicarse en toda la extensión de la cadena productiva, desde el eslabón primario hasta el consumidor.
        .tarjeta.color-primario--claro.p-5
          p.mb-0
            strong Implementarlas requiere especial atención, pero se refleja en los beneficios que se evidenciarán tanto para el productor primario, como para el consumidor final del producto animal, dichos beneficios son:

    .row.justify-content-center
      .col-lg-10
        .row.mb-5
          .col.col-md-6.col-lg-4.mb-4
            figure
              img(src="@/assets/curso/tema3-img3.svg")
          .col.col-md-6.col-lg-4.mb-4
            figure
              img(src="@/assets/curso/tema3-img4.svg")
          .col.col-md-6.col-lg-4.mb-4
            figure
              img(src="@/assets/curso/tema3-img5.svg")
          .col.col-md-6.col-lg-4.mb-4
            figure
              img(src="@/assets/curso/tema3-img6.svg")
          .col.col-md-6.col-lg-4.mb-4
            figure
              img(src="@/assets/curso/tema3-img7.svg")
          .col.col-md-6.col-lg-4.mb-4
            figure
              img(src="@/assets/curso/tema3-img8.svg")
          .col.col-md-6.col-lg-4.mb-4
            figure
              img(src="@/assets/curso/tema3-img9.svg")
          .col.col-md-6.col-lg-4.mb-4
            figure
              img(src="@/assets/curso/tema3-img10.svg")

    Separator(style="visibility: hidden;")

    #t_3_2.titulo-segundo.color-secundario
      h2 3.2  Implementación

    p.mb-5 Para hacer la implementación de las buenas prácticas ganaderas se debe realizar una planeación previa por escrito relacionando las actividades específicas de la unidad productiva, con el fin de ser utilizada como guía de cada proceso y este protocolo pueda ser verificado a través de una plantilla, la cual corrobore que la esta ha sido realizada de forma correcta. En general, los ítems que se deben tener en cuenta son:

    SlyderE(indicadores="centro").px-5.pb-4.mb-5
      .row.ps-5
        .col-md-7.mb-4.mb-md-0
          h3.titulo-tercero Sanidad animal y bioseguridad
          ul.lista-ul--color
            li.mb-0
              i.fas.fa-check
              | Incripción del predio ante el ICA.
            li.mb-0
              i.fas.fa-check
              | Plan sanitario.
            li.mb-0
              i.fas.fa-check
              | Mantener areas de cuarentena, manejo de animales enfermos, control animales nuevos y enfermos.
            li.mb-0
              i.fas.fa-check
              | Control y vacunacion de enfermedades de control.
            li.mb-0
              i.fas.fa-check
              | Plan de bioseguridad.
            li.mb-0
              i.fas.fa-check
              | Mantenimiento de areas vulnerables, manejo de instalaciones, materias primas, elementos y maquinaria en la producción.
            li.mb-0
              i.fas.fa-check
              | Control de plagas, insectos y roedores, animales extraños a la producción.
            li.mb-0
              i.fas.fa-check
              | Limpieza y desinfección en instalación.
            li.mb-0
              i.fas.fa-check
              | Trazabilidad.
        .col-md-5
          figure
            img(src='@/assets/curso/tema3-img11.png')
      .row.ps-5
        .col-md-7.mb-4.mb-md-0
          h3.titulo-tercero Plan de saneamiento
          ul.lista-ul--color
            li.mb-0
              i.fas.fa-check
              | Plan de manejo ambiental manejo integral de residuos.
            li.mb-0
              i.fas.fa-check
              | Prevencion , mitigación y reparacion de riesgos.
            li.mb-0
              i.fas.fa-check
              | Uso eficiente y responsable del agua, suelo, aire.
            li.mb-0
              i.fas.fa-check
              | Minimizar acciones que interfieran con la inocuidad.
        .col-md-5
          figure
            img(src='@/assets/curso/tema3-img12.png')
      .row.ps-5
        .col-md-7.mb-4.mb-md-0
          h3.titulo-tercero Buenas prácticas de uso de medicamentos veterinarios y alimentación animal
          ul.lista-ul--color
            li.mb-0
              i.fas.fa-check
              | Medicamentos, biológicos, plaguicidas y alimentos deben contar con registro del ICA.
            li.mb-0
              i.fas.fa-check
              | Los medicamentos veterinarios, alimentos, biológicos y plaguicidas deben contar con etiqueta, lote, fecha de elaboracion y vencimiento.
            li.mb-0
              i.fas.fa-check
              | Insumos agroecuarios almacenados correctamente y direccionados y registro de los mismos.
            li.mb-0
              i.fas.fa-check
              | Desechar correctamente los envases de medicamentos, biologicos, insecticidas, y otros productos de uso pecuario.
            li.mb-0
              i.fas.fa-check
              | Cuidar los tiempos de retiro de medicamentos, prevenir residuos en productos.
            li.mb-0
              i.fas.fa-check
              | Allimentos y agua de calidad, libre de contaminantes, biologicos, quimicos o fisicos.
        .col-md-5
          figure
            img(src='@/assets/curso/tema3-img13.png')
      .row.ps-5
        .col-md-7.mb-4.mb-md-0
          h3.titulo-tercero Bienestar animal y personal
          ul.lista-ul--color
            li.mb-0
              i.fas.fa-check
              | Proporcionar condiciones de bienestar en la produccion.
            li.mb-0
              i.fas.fa-check
              | La productiva mejora de la mano de las practicas de bienestar y de la mano de obra.
            li.mb-0
              i.fas.fa-check
              | Tener en cuenta la etologia y naturaleza de los animales utilizados en la produccion para brindarles condiciones de bienestar que aumenten la producción.
            li.mb-0
              i.fas.fa-check
              | Capacitar al personal para que tenga acciones apropiadas en los procesos productivos.
            li.mb-0
              i.fas.fa-check
              | Designar al personal necesario de acuerdo a los procesos productivos y el tipo de producción.
        .col-md-5
          figure
            img(src='@/assets/curso/tema3-img14.png')

    .row.justify-content-center.mb-5
      .col-lg-9
        .row.tarjeta.color-primario--claro.p-4
          .col-lg-1
            figure
              img(src="@/assets/curso/tema3-img15.svg")
          .col-lg-11
            p.mb-0 Para la implementación se deben tener en cuenta los requerimientos de la normativa establecida por el ICA (2021) en cada una de las resoluciones por especie en cuanto a procedimientos y documentación, así como se explica en la siguiente tabla.

    .titulo-sexto.color-acento-contenido
      h5 Tabla 1
      span Requerimiento de procedimientos y documentos según la Resolución ICA de acuerdo a la especie

    .tabla-especial.color-acento-contenido
      table
        thead
          tr.color-acento-contenido
            th.text-center.table--new-row Plan de<br>Implementación
            th.text-center.table--new-row Caprinos y Ovinos<br>Res. 2027 / 2018
            th.text-center.table--new-row Porcinos<br>Res. 76509 / 2020
            th.text-center.table--new-row Equinos<br>Res. 7953 / 2017
        tbody
          tr.color-acento-contenido
            td(rowspan="6").fw-bold.table--new-row PROTOCOLOS O PROCEDIMIENTOS
            td Manejo integral de plagas.
            td Manejo integral de plagas.
            td Manejo integral de plagas.
          tr.color-acento-contenido
            td Cuarentena y adquisición de animales.
            td Cuarentena, adquisición de animales, ingreso y aislamiento de reemplazo.
            td Cuarentena y adquisición de animales.
          tr.color-acento-contenido
            td Procedimiento de identificación y atención a cambios de coportamiento -bienestar animal.
            td Procedimiento de identificación y atención a cambios de comportamiento y adaptación o aclimatación - bienestar animal.
            td Procedimiento de identificación y atención a cambios de comportamiento - bienestar animal.
          tr.color-acento-contenido
            td Plan sanitario (manejo y aislamiento anímales enfermos).
            td Plan sanitario y protocolo de bioseguridad.
            td Plan sanitario.
          tr.color-acento-contenido
            td
            td Ingreso y manejo de material genético.
            td
          tr.color-acento-contenido
            td.table--new-row
            td.table--new-row Limpieza de áreas y utensilios.
            td.table--new-row

          tr.color-acento-botones
            td(rowspan="7").fw-bold.table--new-row DOCUMENTOS
            td Registro Único de Vacunación RUV.
            td Registro Único de Vacunación RUV.
            td Registro Único de Vacunación RUV.
          tr.color-acento-botones
            td Prescripciones medicamentos veterinarios - fórmula médica.
            td Prescripciones medicamentos veterinarios - fórmula médica.
            td Prescripciones medicamentos veterinarios - fórmula médica.
          tr.color-acento-botones
            td Formulario o recetario uso de medicamentos de control especial
            td Formulario o recetario uso de medicamentos de control especial
            td Formulario o recetario uso de medicamentos de control especial
          tr.color-acento-botones
            td Instructivo manejo sanitario enfermedades de control oficial.
            td Instructivo manejo sanitario enfermedades de control oficial.
            td Instructivo manejo sanitario enfermedades de control oficial.
          tr.color-acento-botones
            td Resultado del análisis del agua.
            td Autorización aplicación de medicamentos y pequeñas intervenciones quirúrgicas.
            td Examen médico personal.
          tr.color-acento-botones
            td Examen médico personal.
            td Resultado del análisis del agua.
            td Certificados de capacitación.
          tr.color-acento-botones
            td.table--new-row Certificados de capacitación.
            td.table--new-row Certificados de capacitación.
            td.table--new-row Seguridad social.

          tr.color-acento-contenido
            td(rowspan="6").fw-bold.table--new-row REGISTROS
            td Ingresos de personas y vehículos
            td Ingresos de personas y vehículos
            td Ingresos de personas y vehículos
          tr.color-acento-contenido
            td Diagnóstico de enfermedades veterinarias y mortalidad.
            td Diagnóstico de enfermedades veterinarias y mortalidad.
            td Diagnóstico de enfermedades veterinarias y mortalidad.
          tr.color-acento-contenido
            td Aplicación de tratamiento o medicamentos veterinarios.
            td Aplicación de tratamiento o medicamentos veterinarios.
            td Aplicación de tratamiento o medicamentos veterinarios.
          tr.color-acento-contenido
            td Manejo de potreros.
            td Individual o ficha por animal o lote.
            td Inventario de insumos pecuario y agrícolas.
          tr.color-acento-contenido
            td
            td Inventario de productos y biológicos veterinarios.
            td
          tr.color-acento-contenido
            td.table--new-row
            td.table--new-row Inventario de alimentos y materias primas.
            td.table--new-row

          tr.color-acento-botones
            td(rowspan="11").fw-bold.table--new-row ACTIVIDADES DE MANEJO
            td Delimitación del predio y disposición áreas.
            td Delimitación del predio y disposición áreas.
            td Delimitación del predio y disposición áreas.
          tr.color-acento-botones
            td Disposición residuos.
            td Disposición residuos.
            td Disposición residuos.
          tr.color-acento-botones
            td Protección y conservación de fuentes de agua.
            td Protección y conservación de fuentes de agua.
            td Protección y conservación de fuentes de agua.
          tr.color-acento-botones
            td Plagas y roedores.
            td Plagas y roedores.
            td Plagas y roedores.
          tr.color-acento-botones
            td Manejo sanitario.
            td Manejo sanitario.
            td Manejo sanitario.
          tr.color-acento-botones
            td Manejo animal: bienestar animal.
            td Manejo animal: bienestar animal.
            td Manejo animal: bienestar animal.
          tr.color-acento-botones
            td Medicamentos veterinarios.
            td Medicamentos veterinarios.
            td Medicamentos veterinarios.
          tr.color-acento-botones
            td Alimentación animal.
            td Alimentación animal e insumos agropecuarios.
            td Alimentación animal e insumos agropecuarios.
          tr.color-acento-botones
            td Elementos de bioseguridad, elementos de protección personal, seguridad y salud en el trabajo.
            td Bioseguridad.
            td Elementos de bioseguridad, elementos de protección personal, seguridad y salud en las labores del trabajo.
          tr.color-acento-botones
            td
            td Sacrificio humanitario.
            td
          tr.color-acento-botones
            td.table--new-row
            td.table--new-row Elementos e implementos de bioseguridad, elementos de protección personal, seguridad y salud en las labores del trabajo.
            td.table--new-row
</template>

<script>
export default {
  name: 'Tema3',
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
