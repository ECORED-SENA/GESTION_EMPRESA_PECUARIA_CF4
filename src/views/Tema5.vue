<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Programa de producción (concepto y características)

    .row.justify-content-center.mb-5
      .col-lg-7
        p.mb-3 El programa de producción es la actividad principal en la que se reúnen todos los recursos y procesos de la empresa pecuaria que incluyen producción, entre ellos la mano de obra, materias primas, logística, capital o cualquier otra actividad; todas estas actividades se establecen en un lapso de tiempo y en un orden que la da forma al programa en tiempo y jerarquía de procesos, por lo general de ahí se saca un cronograma que será la piedra angular, este es el programa de producción.
        .tarjeta.color-primario--claro.p-5
          p.mb-0 En él se define la necesidad de recursos para cada etapa productiva, en pro de garantizar una operación continua sin interrupciones producto de situaciones previsibles. De esta forma, el programa de producción mitiga los riesgos asociados a la escasez de insumos y personal, así como el incumplimiento de los compromisos adquiridos con terceros por falta de planeación
      .col-lg-5
        figure.px-lg-5
          img(src="@/assets/curso/tema5-img1.png")

    p.mb-5 Su diseño está sometido a los requerimientos efectuados por el área comercial; la satisfacción de la demanda determina los niveles de producción apropiados y la cantidad de recursos y capital necesarios para dar cumplimiento con las expectativas de naturaleza comercial. Así, el programa contempla las exigencias de cada línea productiva, proponiendo la secuencia para la ejecución de labores que resulte más eficiente para optimizar la consecución de los resultados.

    #t_5_1.titulo-segundo.color-secundario
      h2 5.1  Plan de producción

    .row.p-4.mb-5.justify-content-center.align-items-center
      .col-3.col-md-3.col-lg-1.mb-4.mb-lg-0
        figure.px-3
          img(src="@/assets/curso/tema2-img4.svg")
      .col-12.col-md-9.col-lg-11
        p.mb-0 En él se plasman las directrices del programa de producción, definiendo las actividades a llevar a cabo por cada uno de los perfiles involucrados. Su elaboración demanda un conocimiento profundo del área, por cuanto será necesario establecer objetivos individuales para cada fase y determinar el sistema que resulte en la mayor optimización de recursos y tiempo necesarios para llevar a cabo la producción. Esto implica asignar a los funcionarios adecuados y comprender todas las interacciones que se desprendan de la ejecución del trabajo, de tal forma que los tiempos establecidos puedan ser cumplidos a cabalidad.

    .row.mb-4
      .col-lg-9
        .tarjeta.color-primario--claro.p-5.mb-5
          p.mb-0 Un plan de producción puede ser elaborado en función de diferentes horizontes de tiempo, y alcanzar diferentes resultados a partir de ello; sustancialmente podemos distinguir tres (3) categorías:
        LineaTiempoD.color-acento-contenido.mb-5
          .row.align-items-center.pt-3(numero="1" titulo="El plan agregado de producción o Production Plan (PP):")
            .col-lg-2
              figure.px-3
                img(src="@/assets/curso/tema5-img2.svg")
            .col-lg-9
              p.mb-0 se extiende a un año y tiene como objeto de planificación parámetros cuantitativos muy agregados (número de unidades producibles, toneladas de producto acabado, etc., a nivel total o por familias de producto). El objetivo del plan agregado es conciliar la demanda de capacidad productiva (que depende de la demanda de mercado) con la disponibilidad efectiva (expresada en horas-hombre o máquina).
          .row.align-items-center.pt-3(numero="2" titulo="El plan principal de producción o Master Production Schedule (MPS): ")
            .col-lg-2
              figure.px-3
                img(src="@/assets/curso/tema5-img3.svg")
            .col-lg-9
              p.mb-0 concierne a un horizonte temporal limitado (3-4 meses) y tiene como objeto cada uno de los productos acabados. En particular, el MPS tiene el objetivo de dimensionar todos los lotes productivos.
          .row.align-items-center.pt-3(numero="3" titulo="El plan final de monitorización o Final Assembly Schedule (FAS): ")
            .col-lg-2
              figure.px-3
                img(src="@/assets/curso/tema5-img4.svg")
            .col-lg-9
              p.mb-0 concierne a un horizonte temporal muy breve (1 mes) y tiene como objeto el ensamblaje-configuración del producto acabado. La tarea típica del plan es la selección de los modos de elaboración de los pedidos.

    p.mb-5 La característica principal del proceso de planificación de la producción es su carácter cíclico; es decir, que un mismo período puede ser objeto de varias planificaciones sucesivas con crecientes grados de definición. Podemos hablar de fases de planificación y control de la producción: cada fase se abre con la planificación de un período y se concluye con el control que abre la planificación del período siguiente.

    .bloque-texto-a.color-secundario.p-3.p-md-1.mb-5
      .row.m-0.align-items-center.justify-content-between
        .col-lg-3.mb-4.mb-lg-0
          figure.px-3
            img(src="@/assets/curso/tema5-img5.svg")
        .col-lg-9
          .bloque-texto-a__texto.p-3
            p.mb-0 La característica principal del proceso de planificación de la producción es su carácter cíclico; es decir, que un mismo período puede ser objeto de varias planificaciones sucesivas con crecientes grados de definición. Podemos hablar de fases de planificación y control de la producción:
              strong   cada fase se abre con la planificación de un período y se concluye con el control que abre la planificación del período siguiente.

    #t_5_2.titulo-segundo.color-secundario
      h2 5.2  Programación de actividades pecuarias

    p.mb-5 Para elaborar la programación de las actividades pecuarias es necesario seguir algunos pasos con el fin de estructurar estratégicamente un plan que incluya factores como las necesidades de recursos y el cronograma de actividades de acuerdo con los procesos productivos desarrollados, las fases del mismo y el perfil del personal que está disponible, etc. La siguiente infografía muestra en detalle los pasos a seguir en la construcción de la programación:

    .titulo-quinto.color-acento-contenido.mb-5
      h4(style="color: #78B632") Pasos para la construcción de la programación de actividades pecuarias

    .row.justify-content-center
      .col-lg-10
        PasosA.color-acento-botones.mb-5(tipo="n")
          .row
            .col-md-8.mb-4.mb-md-0
              h3 Listar las actividades
              p.mb-0 Se junta una lista con las diversas labores que intervienen en el proceso productivo, evidenciando el tiempo que ocupa cada actividad y el tiempo de inicio más cercano. Además, indicar si cada tarea se puede realizar simultáneamente a otras o debe seguir una secuencia.
            .col-md-3
              figure
                img(src='@/assets/curso/tema5-img6.svg')

          .row
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema5-img7.svg')
            .col-md-8
              h3 Configurar el gráfico
              p.mb-0 Se recomienda el diseño de un diagrama de Gantt, que consiste en una tabla donde las columnas representan intervalos de tiempo, y las filas, las distintas tareas a ejecutar. Puede incluir tareas secuenciales o simultáneas, ya que una misma columna puede ser abordada en diferentes filas, lo que implica la ejecución de diversas tareas en  el mismo periodo de tiempo.

          .row
            .col-md-8.mb-4.mb-md-0
              h3 Analizar el cronograma
              p.mb-0 Para resaltar y diferenciar las tareas o acciones asignadas a los perfiles individuales específicos o equipos responsables; además, se traza una línea de puntos rojos para mostrar la ruta crítica del proceso productivo, destacando las principales actividades a ejecutarse para obtener el producto final.
            .col-md-3
              figure
                img(src='@/assets/curso/tema5-img8.svg')

          .row
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema5-img9.svg')
            .col-md-8
              h3 Supervisar el proceso
              p.mb-0 El seguimiento de la ejecución suele comparar los plazos establecidos en el diagrama de Gantt con los tiempos alcanzados en la ejecución. Es posible que la gráfica requiera ajustes si existen situaciones no contempladas que retrasen algunas tareas, puesto que la secuencialidad demanda la terminación de ciertas labores para continuar con otras. Además, si a juicio del supervisor se hace necesaria la inclusión o eliminación de algunas actividades proyectadas, este tipo de cambios también trae repercusiones directas sobre las estimaciones iniciales.

    .row.justify-content-center
      .col-lg-11
        .tarjeta.color-primario--claro.p-4.mb-5.px-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2-img11.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 Para profundizar más sobre estos conocimientos, se recomienda revisar en el material complementario el video “Anexo 1. Planificación de la Producción Pecuaria” y la cartilla Programación anual de actividades de la finca o a través del siguiente enlace:
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=sfC5IwoNatY" target="_blank")
                    span Ver video
                    i.fas.fa-file-download

    h3.titulo-tercero  Métodos y especificaciones

    .row.justify-content-center.mb-5
      .col-lg-10
        figure
          img(src="@/assets/curso/tema5-img10.svg")

    p.mb-5 Para iniciar se debe definir principalmente la cantidad de aspectos de la producción, especificando a cuál se quiere incursionar, si en la equina, porcina, ovina, avícola, bovina o caprina y qué actividad productiva se va a ejecutar: leche, crías y levante, producción de carne, huevo, lana, etc. Pero además qué tipo de sistema se va a utilizar: intensivo, extensivo, semiintensivo, en piso, pastoreo por franjas, sistemas silvopastoriles, en corral, etc., si la empresa es propia, en compañía o por arrendamiento, etc. Una vez aclarado estos puntos se podrán precisar la ubicación más apropiada para las instalaciones de la unidad productiva, así como las instalaciones y sus adecuaciones, elementos, materiales, insumos, razas más apropiadas de animales, cantidad de los mismos, entre otras cosas.
      br
      br
      strong Ya a partir de aquí, se pueden tener en cuenta las siguientes especificaciones para programar la producción:

    .row.justify-content-center
      .col-lg-9
        .tarjeta.color-primario--claro.p-5.mb-5
          p.mb-0
            strong Plan de acción.
            |    En esta herramienta se plasman y agendan las actividades diarias, semanales, mensuales y anuales trazándolas en una línea de tiempo determinada, en donde preguntas como qué se va a producir, qué productos se va a ofrecer y cómo, cuál será la línea de comercialización. Además, hay otros procesos que deben ser realizados como el registro de costos, gastos, presupuesto y en cuanto a personal conocer el número de trabajadores, perfiles, cargos, remuneraciones, horarios y demás.
        .tarjeta.color-primario--claro.p-5.mb-5
          p.mb-0
            strong Ejecución.
            |    Luego de que se hayan realizado con éxito las actividades anteriores se debe dar marcha a la ejecución del plan procurando que todo sea exitoso. También es posible realizar cambios y modificaciones en caso de que ciertos aspectos o actividades no estén funcionando, hasta llegar a desarrollar un plan o estrategia efectiva para su modelo de negocio.

    Separador(style="visibility: hidden;")

    h3.titulo-tercero Labores Pecuarias

    p.mb-5 Las labores pecuarias se refieren a esas actividades relacionadas con la fase económica de la ganadería. Son una derivación principal de las labores agropecuarias y forman parte integral del sector primario de la economía. Estas labores cumplen un papel de vital importancia en las comunidades rurales ayudándoles a mejorar la alimentación, ingresos, productividad, transporte, trabajo, entre otras, lo cual se traduce en bienestar.
      br
      br
      strong Desde el punto de vista objetivo las labores pecuarias ocupan un lugar importante en los siguientes aspectos:

    .titulo-sexto.color-acento-contenido.mb-5
      h5 Figura 5
      span Importancia de las labores pecuarias

    .row.justify-content-center.mb-4.align-items-center.contenedor-imagen-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema5-img11.svg")
      .col-lg-8
        div
          h3.titulo-tercero Suministro de alimentos
          p.mb-0 Ofrece un gran aporte en el abastecimiento de producto alimenticio contribuyendo a la nutrición a través del suministro de proteínas como leche, huevos y carne además de otros productos de consumo como pieles, abonos y fertilizantes.
    .row.justify-content-center.mb-4.align-items-center.contenedor-imagen-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema5-img12.svg")
      .col-lg-8
        div
          h3.titulo-tercero Producción agrícola
          p.mb-0 La utilización del ganado y sus subproductos como las heces, es importante en la producción agrícola, mejorando la estructura y fertilidad del suelo, el ganado también se usa como transporte, llevando insumos, productos agrícolas y/o personas. Destacándose, además, que estas labores contribuyen al medio ambiente.
    .row.justify-content-center.align-items-center.contenedor-imagen-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema5-img13.svg")
      .col-lg-8
        div
          h3.titulo-tercero Seguridad financiera
          p.mb-0 El ganado en sí, representa un activo y, por ende ,se puede convertir en efectivo o ser garante para un préstamo, lo cual es de importancia en la econmia familiar rural.


</template>

<script>
export default {
  name: 'Tema5',
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
