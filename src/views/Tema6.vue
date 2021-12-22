<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.no-border.bottom-left.bottom-right

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Plan sanitario

    .row.justify-content-center.mb-5
      .col-lg-7
        p.mb-4 El plan sanitario en las producciones pecuarias es de gran importancia, puesto que este garantiza que se disminuyan los problemas que puedan afectar el sistema de producción y afecten la capacidad productiva y reproductiva en las explotaciones.
        .cajon.color-primario.p-4.mb-4
          p.mb-0 Este plan debe estar enfocado en establecer actividades que contribuyan de manera sistemática, ordenada, integrada y práctica con la prevención, el control y la erradicación de enfermedades de control oficial y de gran incidencia en las producciones pecuarias. En síntesis, el plan sanitario debe establecer actividades que estén diseñadas en la mitigación de factores de riesgo que puedan afectar la sanidad de los animales.
        p.mb-4 Es de aclarar que, aunque se tienen actividades en común (manejo, vacunación, desparasitación), cada plan sanitario debe ser diseñado para las condiciones específicas de cada predio en singular y a su sistema de manejo, ya que las condiciones de varían entre una región y otra, inclusive entre predios.
      .col-lg-5
        figure
          img(src="@/assets/curso/tema6-img1.png")

    p.mb-5 En la figura que se muestra a continuación, se puede observar la estructura general que se recomienda para establecer un plan sanitario y los pasos para su elaboración:

    .row.justify-content-center
      .col-lg-10
        .row.mb-5
          .col-lg-3
            figure
              img(src="@/assets/curso/tema6-img2.svg")
          .col-lg-9
            TabsA.color-acento-botones.mb-5
              .tarjeta.color-acento-botones.p-4(titulo="<i class=\"fas fa-chevron-down\"><\/i> Alcance")
                p.py-5.mb-0 En esta fase se explica el contexto de aplicación del plan, el personal encargado de aplicarlo y a quien va dirigido.
              .tarjeta.color-acento-botones.p-4(titulo="<i class=\"fas fa-chevron-down\"><\/i> Objeto")
                p.py-5.mb-0 Aquí se debe mencionar la intención que se tiene al implementar el plan.
              .tarjeta.color-acento-botones.p-4(titulo="<i class=\"fas fa-chevron-down\"><\/i> Consideraciones")
                p.py-5.mb-0 Se deben mencionar las consideraciones a tener en cuenta en el momento de la implementación del plan sanitario, las palabras con mayor importancia para la comprensión del plan. Deben describirse las causas que pueden generar algunos peligros o enfermedades, como prevenirlas y los tratamientos.
              .tarjeta.color-acento-botones.p-4(titulo="<i class=\"fas fa-chevron-down\"><\/i> Desarrollo")
                p.py-5.mb-0 Se plasman todas las actividades y fechas para la implementación del plan.
              .tarjeta.color-acento-botones.p-4(titulo="<i class=\"fas fa-chevron-down\"><\/i> Registros")
                p.py-5.mb-0 La información de todas las actividades que se desarrollen en el marco del plan, se deben consignar en los registros.

        p.mb-5 En relación con la elaboración del plan sanitario se recomienda tener en cuenta la siguiente estructura:

        .titulo-sexto.color-acento-contenido.mb-5
          h5 Figura 6.
          span Estructura de un plan sanitario.

        figure.mb-5
          img(src="@/assets/curso/tema6-img3.svg")

        Separador

    #t_6_1.titulo-segundo.color-secundario
      h2 6.1  Prevención de enfermedades de control oficial

    .row.mb-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema6-img5.svg")
      .col-lg-8
        figure.mb-4.text-right.w-auto
          img(src="@/assets/curso/tema6-img4.svg" style="height: 40px; width: auto;")
        p.mb-0 Las enfermedades de control oficial son aquellas que, de acuerdo con lo establecido en las normas internacionales adoptadas por Colombia, se establecen como de interés en el ámbito nacional y se disponen programas de prevención, control y erradicación. De igual manera, se establece su notificación obligatoria y registro. A continuación, encuentra el listado de enfermedades y sus características principales:


  .container.tarjeta.tarjeta--naranja.p-4.p-md-5.no-border.top-left.top-right.bottom-left.bottom-right
    p.mb-5.px-5.color-texto-naranja.text-center Enfermedades de control oficial
    p.mb-5.px-5 Son las enfermedades que pueden sufrir las especies pecuarias y que se deben trabajar de inmediato por parte del predio y el ICA que es la entidad encargada de priorizar dichas enfermedades para evitar problemas mayores que impacten el proceso productivo, las enfermedades que han sido declaradas de control oficial en Colombia por el ICA y para las cuales se debe vacunar obligatoriamente son:

    TabsSpecial
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-1.svg')")
        p.mb-5
          strong Fiebre aftosa
          br
          br
          | Enfermedad viral altamente contagiosa que puede afectar a los animales de pezuña hendida como los bovinos, ovinos, caprinos, porcinos, bufalinos, venados y camélidos. El agente etiológico es un virus de la familia Picornaviridae género Aphtovirus y actualmente existen siete serotipos el O, A, C, SAT1, SAT2, SAT3 y Asia1.
        .cajon.color-primario.p-4.mb-4
          p.mb-0
            strong Sus signos clínicos más representativos son:
            |   presencia de ampollas y aftas en la lengua, paladar, encías, espacios interdigitales y/o ubre. Además de los mencionados anteriormente, los animales también pueden presentar fiebre, salivación excesiva, inapetencia, disminución en la producción de carne o leche, mastitis, cojeras, deformación de los cascos.
        p.mb-0 Esta enfermedad es altamente propagable y se transmite de a través de la orina, heces, saliva, gotículas y leche de los animales infectados. Su prevención se hace vacunando los animales de cualquier edad y repetir la dosis cada 6 meses.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-2.svg')")
        p.mb-5
          strong Estomatitis vesicular
          br
          br
          | Es una enfermedad que se presenta principalmente bajo los 2.500 msnm. Su agente etiológico es un virus de la familia Rhabdoviridae, género Vesiculoris y existen dos serotipos principales: New Jersey e Indiana. Sus principales huéspedes son, los equinos, mulares, asnales, bovinos y porcinos.
        .cajon.color-primario.p-4.mb-4
          p.mb-0
            strong Sus signos clínicos más representativos son:
            |   suelen confundirse con los de la fiebre aftosa, ya que los animales infectados presentan: presencia de ampollas y aftas en la lengua, paladar, encías, espacios interdigitales y/o ubre. Además de los mencionados anteriormente, los animales también pueden manifestar fiebre, salivación excesiva, inapetencia, disminución en la producción de carne o leche, mastitis, cojeras, deformación de los cascos.
        p.mb-0 El tratamiento de esta enfermedad es estrictamente sintomático y se realiza limpiando las heridas con una solución antiséptica y brindando alimento blando a los animales que presenten lesiones en la boca.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-3.svg')")
        p.mb-5
          strong Brucelosis
          br
          br
          | Es una enfermedad infecciosa, causada por una bacteria Brucella. Existen diferentes especies de Brucella dependiendo de su huésped natural: Brucella abortus (bovinos), Brucella melitensis (ovinos y caprinos), Brucella ovis (ovinos), Brucella suis (porcinos), Brucella canis (caninos), Brucella neotomae (roedores silvestres).
        .cajon.color-primario.p-4.mb-4
          p.mb-0
            strong Sus signos clínicos más representativos son:
            |   abortos en el último tercio de la gestación, nacimiento de crías débiles, retención de placenta, metritis, en la macho orquitis y causar problemas de fertilidad en el hato. Además, es una enfermedad zoonótica, es decir, que se puede transmitir a los humanos. Puede afectar bovinos, ovinos, caprinos, caninos, al ser humano, entre otros. El hombre se puede contaminar por el consumo de leches crudas o por el contacto con secreciones de animales enfermos o fetos.
        p.mb-0 Su prevención consiste en vacunar exclusivamente las hembras entre 3 y 8 meses de edad con la vacuna cepa 19. Para el caso de las hembras mayores de 8 meses de edad, está rotundamente prohibida la vacunación con cepa 19 y solo se podrá vacunar con cepa RB51 con previa autorización del ICA. De igual manera, está totalmente prohibido el uso de estas vacunas en machos.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-4.svg')")
        p.mb-5
          strong Tuberculosis
          br
          br
          | Enfermedad infectocontagiosa, zoonótica, crónica, producida por bacterias de morfología bacilar pertenecientes al género Mycobacterium, incluyendo las especies Bovis, Tuberculosis y Avium. Esta enfermedad afecta principalmente a los bovinos, ovinos, caprinos, cerdos, aves, humanos, entre otros. En los humanos se transmite por el consumo de leches crudas o quesos frescos. En los animales se transmite a través de secreciones o excreciones, también se pueden contaminar a través de objetos contaminados como suelo, agua, pasto, alimento o vía aerógena.
        .cajon.color-primario.p-4.mb-4
          p.mb-0
            strong Sus signos clínicos más representativos son:
            |   tos seca, debilidad progresiva, perdida del apetito, fiebre fluctuante, dificultad para respirar (disnea), ganglios linfáticos grandes. Una de las lesiones más características es que en los pulmones se aprecian áreas de gran tamaño con apariencia caseificada y zonas de mineralización.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-5.svg')")
        p.mb-5
          strong Encefalopatía Espongiforme Bovina (EEB)
          br
          br
          | Comúnmente conocida con la “enfermedad de las vacas locas”, es una enfermedad zoonótica, exótica en Colombia, progresiva y fatal del sistema nervioso bovino. Es causada por la acumulación de una proteína anormal en el tejido nervioso y denominada prion y se distinguen dos formas:  la primera es la forma clásica que se da en los bovinos tras la ingestión del prion en piensos contaminados, específicamente ocurre cuando el alimento contiene productos derivados de bovinos como la harina de sangre o de hueso. La segunda forma es la atípica que hace referencia a la aparición de la enfermedad de forma espontánea.
        .cajon.color-primario.p-4.mb-4
          p.mb-0
            strong Sus signos clínicos más representativos son:
            |   comportamiento agresivo o nervioso, falta de coordinación y dificultad para levantarse de la posición de reposo, hipersensibilidad al sonido y al tacto, movimientos espasmódicos, temblores, depresión, postura anormal, pérdida de peso, postura anormal de la cabeza, temblores y ataxia, desplazamientos en círculos, golpeo de miembros, lamido excesivo, bruxismo
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-6.svg')")
        p.mb-5
          strong Rabia silvestre
          br
          br
          | Esta es una enfermedad viral, de tipo nervioso y que es prevenible de los mamíferos. El virus de la rabia infecta el sistema nervioso central y puede llegar a causar la muerte. Afecta a los animales domésticos como bovinos, equinos, ovinos, caprinos, porcinos, caninos y felinos. Se considera además una de las principales enfermedades zoonóticas. La principal vía de contaminación es a través de la saliva de animales infectados, generalmente se da por mordeduras, aunque también se puede contaminar a través de las membranas mucosas (boca, nariz y ojos). En Colombia, los mayores transmisores de la enfermedad son los murciélagos hematófagos.
        .cajon.color-primario.p-4.mb-4
          p.mb-0
            strong Sus signos clínicos más representativos son:
            |   cambios en el comportamiento, caída e incoordinación del tren posterior, salivación abundante, ceguera, temblores musculares y parálisis. Los animales presentan además pérdida de peso progresivo y deshidratación y posteriormente la muerte. La prevención se realiza a través de vacunación y control de murciélagos hematófagos.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-7.svg')")
        p.mb-5
          strong Enfermedad de Newcastle
          br
          br
          | Conocida comúnmente como peste, moquillo o ahogazón. La enfermedad de Newcastle es una infección altamente contagiosa y con frecuencia severa, causada por un virus de la familia de los Paramyxovirus, de distribución cosmopolita. Tiene tres presentaciones: lentogénica o leve, mesogénica o moderada, y velogénica o muy virulenta, el virus puede sobrevivir por largos periodos a temperatura ambiente, especialmente en las heces, pero puede ser destruido por varios agentes físicos y químicos, no resiste pH ácidos ni la exposición a temperaturas de 60 °C por más de 30 min, es sensible al éter, formalina, amonios cuaternarios, agentes fenólicos y oxidantes, clorhexidina e hipoclorito de sodio (6%). El período de incubación es de 2 a 15 días, pero para efectos del código terrestre de la OIE es de 21.
        .cajon.color-primario.p-4.mb-4
          p.mb-0 En la mayor parte de países con producción avícola a escala comercial, se practica la vacunación profiláctica. Para demostrar que un país está libre de la enfermedad de Newcastle, es necesaria la vigilancia conforme a las directrices del Código Sanitario para los Animales Terrestres de la OIE. En última instancia, los productores avícolas deben establecer procedimientos eficaces de bioseguridad para evitar la introducción de la enfermedad (Código Sanitario para los Animales Terrestres de la OIE).
        p.mb-0 Para profundizar más sobre la enfermedad de Newcastle se recomienda leer la cartilla Conceptos importantes para tener en cuenta para el control y diagnóstico de la enfermedad de Newcastle disponible en el material complementario.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-8.svg')")
        p.mb-5
          strong Encefalitis Equina Venezolana (EEV)
          br
          br
          | Es una enfermedad que afecta a los equinos y también a los humanos, es causada por un virus de la familia Togaviridae, este virus se transmite por la picadura del mosquito. Se puede prevenir vacunando cada dos años los equinos que habitan en los municipios que se encuentran por debajo de los 1.200 msnm. Es requisito indispensable para la movilización de equinos, que se encuentren vacunados contra la EEV y deberá realizarse con un periodo de anticipación de 15 días antes de la movilización de los animales.
        .cajon.color-primario.p-4.mb-4
          p.mb-0
            strong Sus signos clínicos más representativos son:
            |   en los humanos: fiebre mayor de 40 grados, dolor de cabeza, catarro nasal, vómito y dolores musculares. Sin embargo, algunas personas pueden presentar síntomas neurológicos como rigidez de la nuca, convulsiones, desviación ocular, nistagmos y en casos extremos, la muerte.
            br
            br
            | En los equinos: fiebre, inapetencia, depresión, exitabilidad, apoyar la cabeza en paredes o superficies, caminar en círculos, movimientos masticatorios, flacidez en los labios, ojos semicerrados y orejas caídas.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-9.svg')")
        p.mb-5
          strong Peste Porcina Clásica (PPC)
          br
          br
          | Enfermedad viral, altamente contagiosa, que afecta a cerdos domésticos y silvestres y producida por un virus de la familia Flaviviridae del género Pestivirus. Por sus características, y por no existir tratamiento, es la enfermedad más importante en los porcinos a nivel mundial. La transmisión puede hacerse por contacto directo entre los cerdos vía oral u oro nasal, aunque también se pueden contagiar por contacto indirecto.
        .cajon.color-primario.p-4.mb-4
          p.mb-0
            strong Sus signos clínicos más representativos son:
            |   varían dependiendo de la cepa, la edad del animal y el estado inmunitario del mismo, mostrando varias formas de la enfermedad:
        .row.justify-content-center
          .col-lg-10
            .tarjeta.tarjeta-slide.derecha.color-acento-botones.mb-3(@mouseover="indicadorTarjetaSlide = false")
              .tarjeta-slide__contenedor
                .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema6-img7.svg')})`}")
                .tarjeta-slide__contenido.p-4.p-xl-5
                  p.mb-0 Los animales muestran letargia y posteriormente la muerte en un periodo entre 24 a 48 posteriores a la infección. Aunque las lesiones suelen ser inespecíficas, se pueden encontrar congestión del tracto gastrointestinal, el hígado, y los pulmones.
            .tarjeta.tarjeta-slide.izquierda.color-primario.mb-3(@mouseover="indicadorTarjetaSlide = false")
              .tarjeta-slide__contenedor
                .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema6-img8.svg')})`}")
                .tarjeta-slide__contenido.p-4.p-xl-5
                  p.mb-0 En esta forma, los animales presentan síntomas como fiebre, letargia, hemorragias y cianosis en la piel, disnea, tos, convulsiones, ataxia, anorexia, estreñimiento seguido de diarrea con sangre, y una mortalidad de casi 100%. Las lesiones que suelen encontrarse son principalmente petequias en los riñones, vejiga, bazo, laringe y ganglios linfáticos.
            .tarjeta.tarjeta-slide.izquierda.color-secundario.mb-3(@mouseover="indicadorTarjetaSlide = false")
              .tarjeta-slide__contenedor
                .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema6-img9.svg')})`}")
                .tarjeta-slide__contenido.p-4.p-xl-5
                  p.mb-0 Los síntomas presentes en esta forma son muy parecidos a los de la forma anterior; pero con una intensidad menor. Aquí, el curso de la enfermedad es más lento y la tasa de mortalidad es menor a 30%. Las lesiones que se encuentran son presencia de úlceras botonosas en el intestino y áreas de necrosis circulares y concéntricas muy bien delimitadas.
            .tarjeta.tarjeta-slide.izquierda.color-acento-contenido.mb-3(@mouseover="indicadorTarjetaSlide = false")
              .tarjeta-slide__contenedor
                .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema6-img10.svg')})`}")
                .tarjeta-slide__contenido.p-4.p-xl-5
                  p.mb-0 Los síntomas son de curso muy lento y se presentan fiebres intermitentes, postración, apetito irregular, tos, diarrea, aborto, infecciones bacterianas secundarias y aparente recuperación con recaída y finalmente la muerte. Las lesiones que se encuentran en esta forma son ulceras botonosas en el ciego y el intestino grueso, enteritis difterioide difusa.
            .tarjeta.tarjeta-slide.derecha.color-acento-botones.mb-5(@mouseover="indicadorTarjetaSlide = false")
              .tarjeta-slide__contenedor
                .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema6-img11.svg')})`}")
                .tarjeta-slide__contenido.p-4.p-xl-5
                  p.mb-0 Esta forma se identifica al observar lechones nacidos débiles o muertos, malformaciones fetales, momificaciones. Es importante aclarar que los lechones que sobreviven se convierten en portadores al presentar la infección congénita persistente.
            p.mb-0.text-center Dentro de las medidas de prevención para la PPC se encuentra la bioseguridad del predio, el control a las movilizaciones de animales y la vacunación de animales.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-10.svg')")
        p.mb-5
          strong Influenza aviar
          br
          br
          | Es una infección viral tipo que afecta a todo tipo de aves, generalmente causa infecciones transitorias e inaparentes en aves silvestres (principalmente aves acuáticas) y no plantea serias amenazas a la salud de la vida silvestre, aves domésticas u otras especies. Sin embargo, ocasionalmente una cepa del virus de la IA puede emerger como una significativa amenaza a las aves silvestres, la industria aviar y/o a la salud humana; estas cepas son llamadas cepas de “influenza aviar altamente patógena” HPAI (del inglés Highly Pathogenic Avian Influenza).
        .cajon.color-primario.p-4.mb-4
          p.mb-0 La transmisión se produce por el contacto directo con las secreciones de aves infectadas, especialmente a través de las heces o de los alimentos y el agua contaminados, se puede diseminar por el transporte de fómites contaminados tales como agua, alimentos, implementos, sacos, botas, ropa, bandejas, cajas de huevos, entre otros. El virus también está normalmente en los tractos respiratorios o intestinales de las aves silvestres que actúan como portadores, transportando al virus  largas distancias cuando realizan sus migraciones. Los síntomas son depresión leve a severa, disminución en consumo de alimento, tos, estornudo, lagrimeo, cresta y barbilla congestionada y edematosa, aumento en la mortalidad.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-11.svg')")
        p.mb-5
          strong Salmonelosis
          br
          br
          | La salmonelosis es una enfermedad causada por bacterias del género Salmonella de la cual existen más de 2.600 serotipos, siendo los más importantes en el ámbito de la avicultura y a los cuales el ICA realiza actividades de control son S. pullorum y S. gallinarum, de una distribución cosmopolita, afecta a todo tipo de aves,  con gran resistencia a la desecación, pueden sobrevivir en ambiente sobre todo en presencia de materia orgánica (heces, cáscara de huevo, cama entre otros) durante varios días, aunque es susceptible a sustancias químicas oxidantes. S. pullorum y S. gallinarum, son inmóviles y altamente patógenas para las aves de corral, pudiendo causar altas pérdidas en animales reproductores o en la progenie. Además, estas bacterias pueden infectar otras especies de aves y algunos mamíferos.
        .cajon.color-primario.p-4.mb-4
          p.mb-0
            strong Sus signos clínicos más representativos son:
            |   en  general comprenden  anorexia, diarrea, deshidratación, amontonamiento, adherencia de heces a la cloaca, debilidad y muerte, pero específicamente depende del serovar por ejemplo en Pulorosis los síntomas son diarrea blanquecina abundante, que causa “empastamiento o taponamiento” de los pollitos, dificultad para respirar, tarsos inflamados, somnolencia, depresión y con crecimiento retardado, nódulos grisáceos blanquecinos en corazón, pulmones, hígado, paredes de molleja e intestino.
      .py-4.pt-md-3.pb-md-5.px-md-5(:icono="require('@/assets/curso/tab-position-12.svg')")
        p.mb-5 Cada una de las enfermedades tratadas en esta presentación son de suma urgencia, en caso de identificar alguno de los síntomas o tiene certeza de la enfermedad por favor llame al veterinario y reporte al ICA de inmediato.
          br
          br
          | Todos los datos de contacto los puede encontrar en:
        .row.justify-content-center
          .col-lg-10
            figure.image-click(@click="openImage('https://www.ica.gov.co')")
              img(src="@/assets/curso/tema6-img12.svg")

  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.no-border.top-left.top-right.bottom-left.bottom-right
    .row.justify-content-center
      .col-lg-9
        p.mb-5 Alerta temprana es la forma de llamar a las acciones que deben ser tenidas en cuenta con prioridad para el beneficio de las diferentes fincas evitando la propagación de alguna enfermedad o virus; por ello, a continuación, se comparte la imagen del ICA con estas alertas y se recomienda contactar de inmediato al Instituto para reportar la urgencia en caso de evidenciarla:
        figure.image-click(@click="openImage(obtenerLink('/downloads/sistema-de-alerta-temprana.jpg'))")
          img(src="@/assets/curso/tema6-img6.svg")

    Separador.mb-0

  .container.tarjeta.tarjeta--gris-especial.p-4.p-md-5.py-0.py-md-0.no-border.top-left.top-right.bottom-left.bottom-right

    #t_6_2.titulo-segundo.color-secundario
      h2 6.2  Área de cuarentena

    p.mb-5 La cuarentena pecuaria comprende todas aquellas medidas encaminadas a regular, restringir o prohibir la producción o la importación de animales y sus productos y restringir el movimiento o existencia de estos, con la finalidad de prevenir la introducción, dispersión o diseminación de enfermedades u otros organismos que afectan o puedan afectar la sanidad animal del país.

    .row.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema6-img13.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El área de cuarentena es un área física y específica de la producción en donde se deben cumplir unas condiciones de aislamiento de los animales que se van a ingresar nuevos al predio o que se sospecha que tienen alguna enfermedad o condición contagiosa.
              br
              br
              | En cuanto a los requisitos estructurales, esta área debe estar separada de otras zonas donde haya animales, y por supuesto, a una distancia prudente, dependiendo de la especie animal y la capacidad de difusión en el aire de posibles agentes patógenos.
        p.mb-5 Esta zona debe estar delimitada por muros, vallas o alambrados, con puerta y un aviso en la entrada que alerte sobre la prohibición del ingreso de personal no autorizado. Estas medidas son muy importantes ya que se pueden diseminar los agentes patógenos por toda la producción. Debe tener una zona de cargue y descargue de animales y en lo posible contar con un vestier donde el operario pueda realizar el cambio de vestuario y botas y si se requiere, ducharse.

    Separador

  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.py-0.py-md-0.no-border.top-left.top-right.bottom-left.bottom-right

    #t_6_3.titulo-segundo.color-secundario
      h2 6.3  Almacenamiento y transporte de productos biológicos y medicamentos veterinarios

    p.mb-4 Los medicamentos son sustancias utilizadas para curar a los animales y su administración puede ser interna o externa. Por otra parte, los biológicos son sustancias utilizadas para la prevención de enfermedades, como por ejemplo las vacunas. Los medicamentos veterinarios que se utilizan y comercializan en Colombia, deben estar registrados ante el Instituto Colombiano Agropecuario (ICA) y deberán emplearse aplicando las buenas prácticas para el uso de medicamentos veterinarios.

    .cajon.color-acento-contenido.p-4.mb-4
      p.mb-0 Pueden clasificarse de acuerdo con: su naturaleza (farmacológico o inmunológico); su vía de administración (oral, inyectable, ocular, por nebulización), sus propiedades (analgésico, antiparasitario, anestésico), su forma farmacéutica (polvo oral, premezcla medicamentosa, aerosol, comprimido, entre otros).

    p.mb-5.text-center Los medicamentos tienen varias formas de presentación, y se clasifican según su forma de elaboración así:

    .row.justify-content-center
      .col-lg-10
        figure
          img(src="@/assets/curso/tema6-img14.svg")
        .p-4.px-5.caja-texto-subrayado.mb-4
          p.mb-0 Las condiciones de almacenamiento, transporte y conservación deben ajustarse a las especificaciones que figuran en la etiqueta, en particular las relativas a la temperatura, luz y humedad.
        p.mb-0 Todos los productos veterinarios deben almacenarse en instalaciones seguras y mantenerse bajo llave fuera del alcance de los niños y los animales. Los medicamentos se almacenan separados de los plaguicidas, fertilizantes y alimentos.

    Separador

    #t_6_4.titulo-segundo.color-secundario
      h2 6.4  Técnicas para aplicación de medicamentos veterinarios

    .row.mb-5
      .col-lg-8
        p.mb-0 Se debe tener muy en cuenta que, “con el uso de medicamentos en las especies pecuarias, se pueden generar algunos riesgos que están principalmente vinculados con su manipulación y administración” (Invima, 2020). Por lo anterior, las autoridades competentes deben establecer y aplicar la regulación sobre las buenas prácticas de uso de medicamentos veterinarios.
          br
          br
          | Para poder aplicar las técnicas de aplicación de medicamentos veterinarios se deben tener en cuenta factores como la seguridad, el costo, la efectividad, la especie que se vaya a tratar, el tipo de enfermedad (agudo o crónico), el manejo (dominancia sobre el animal), la vía de administración y la forma farmacéutica.
      .col-lg-4
        figure
          img(src="@/assets/curso/tema6-img15.svg")

    .box-soft-green.py-2.px-5.mb-5
      p.mb-0 Las vías de aplicación de medicamentos varían dependiendo de la especie animal; sin embargo, las principales vías de aplicación de medicamentos son:

    .row.justify-content-center.mb-5
      .col-md-11.col-lg-7
        SlyderF(columnas="col-12").mb-5
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong Intraalar:
              |   se realiza punzando la membrana del ala. Específicamente, en medio del triángulo formado por el pliegue que aparece al abrir el ala. Este método es el utilizado para realizar vacunaciones contra Viruela Aviar y se realiza con aplicador de doble estilete que previamente debe ser introducido en el frasco que contiene la vacuna.
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong Intramamaria:
              |   con la ayuda de un catéter de pezón, se aplica el medicamento en los pezones del animal. Esta técnica es muy utilizada para tratar casos de mastitis o secados de vacas productoras de leche.
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong In ovo:
              |   se inyecta a los embriones en su último estado de incubación.
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong Intranasal:
              |   el medicamento se aplica por los orificios nasales. Las formas más utilizadas son en gotas, nebulizaciones o también se puede emplear el uso de una jeringa para medicamentos líquidos y se utilizan principalmente en especies pecuarias que presenten problemas respiratorios.
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong Oftálmica:
              |   este método de aplicación es muy utilizada en aves y consiste en la aplicación directa del medicamento sobre el ojo del animal, generalmente la presentación del medicamento viene en gotas y se utiliza mucho en vacunaciones e infecciones oculares. Se aplica el medicamento directamente sobre el ojo. Este método es de manejo individual de los animales y en las aves se utiliza principalmente para realizar vacunaciones contra enfermedades como Newcastle, Gumboro, bronquitis, entre otras.
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong Ótica:
              |   el medicamento es aplicado en el oído y suele utilizarse mayormente en infecciones de oído medio o externo.
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong Oral:
              |   el medicamento se aplica por la boca o pico, según sea el caso, y se emplean medicamentos en presentaciones de pastillas, polvos, jarabes, suspensiones. En las aves es la principal vía de administración.
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong Rectal:
              |   se aplica el medicamento por el recto y se utilizan en formas de supositorios o lavados.
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong Tópica:
              |   el medicamento se aplica sobre la piel del animal y su presentación puede ser en crema, líquido, aerosol, polvo. Esta vía de aplicación se utiliza principalmente en heridas.
          .tarjeta.tarjeta--naranja-2.p-5
            p.mb-0
              strong Intravaginal e Intrauterina:
              |   con la ayuda de un catéter, se aplica el medicamento directamente por la vagina del animal o en el caso de ser intrauterina, se continúa introduciendo el catéter pasando por el cuello uterino hasta llegar al útero y poder depositar el medicamento allí. Esta técnica se utiliza principalmente en casos de metritis o infecciones vaginales.


        p.mb-5 La siguiente vía es la <strong>parenteral</strong> y se compone de varios elementos que se deben tener en cuenta. Esta vía implica la ruptura de las barreras del organismo, la piel y las mucosas para depositar las sustancias en tejidos o cavidades internas del organismo inyectando el medicamento a través de una punción utilizando aguja y jeringa desechables. A continuación, se explican varias vías de aplicación de medicamentos parenteral:

        figure.mb-5
          img(src="@/assets/curso/tema6-img16.jpg")

        p.mb-5 Posterior a definir la técnica a trabajar se requiere definir la vía de administración y en la siguiente infografía se trabajan las más frecuentes:

        SlyderF(columnas="col-12")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img17.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img18.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img19.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img20.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img21.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img22.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img23.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img24.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img25.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img26.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img27.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img28.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img29.svg")
          .tarjeta.tarjeta--naranja-2
            figure
              img(src="@/assets/curso/tema6-img30.svg")

    Separador

    #t_6_5.titulo-segundo.color-secundario
      h2 6.5  Tiempo de retiro

    .cajon.color-acento-contenido.p-4.mb-4
      p.mb-0 Este tiempo que debe reposar aislado un animal desde la hora de aplicación del medicamento veterinario hasta la eliminación del medicamento del cuerpo su organismo logrando disminuir como mínimo hasta que la concentración del producto médico no infrinja el Límite Máximo de Residuos (LMR) en los tejidos del animal, esto tiene el fin de evitar que esa carne o esos productos dependientes de los animales no sean dañosos para la salud de los seres humanos o los animales con los que el animal intervenido tenga contacto. Este tiempo debe ser respetado tal como se enuncia a continuación:

    PasosA.color-primario.mb-5(tipo="n")
      .row
        .col-md-7.mb-4.mb-md-0
          p.mb-0 La mayoría de los medicamentos veterinarios tienen establecidos los tiempos de retiro en las etiquetas de los productos. Como se mencionó anteriormente, el tiempo de retiro no garantiza que no existan residuos de medicamentos en los productos destinados para el consumo humano, sino que los niveles de este medicamento se encuentran por debajo del LMR.
        .col-md-4
          figure
            img(src='@/assets/curso/tema6-img37.png')

      .row
        .col-md-4.mb-4.mb-md-0
          figure
            img(src='@/assets/curso/tema6-img38.png')
        .col-md-7
          p.mb-4 Cabe resaltar que la FAO en su Codex Alimentarius CX/MRL 2-2018, establece los límites máximos de residuos y las recomendaciones sobre la gestión de riesgos para residuos de medicamentos veterinarios en los alimentos. De igual manera, en Colombia existe la Resolución 1382 de 2013, por la cual se establecen los límites máximos para residuos de medicamentos veterinarios en los alimentos de origen animal, destinados al consumo humano.
          .row
            .col-lg-6.col-md-8.col-12
              a.anexo.mb-4(:href="obtenerLink('/downloads/global-goals.jpg')" target="_blank")
                .anexo__icono
                  img(src="@/assets/curso/jpg-link.svg")
                .anexo__texto
                  p <strong>Anexo</strong>. The global goals.


      .row
        .col-md-7.mb-4.mb-md-0
          p.mb-0 Los medicamentos se deben utilizar de forma responsable, ya que existen algunos productores que tienen la creencia que siempre se debe aplicar mucho más de la dosis recomendada en la etiqueta y, por consiguiente, el tiempo de retiro será diferente, ya que este deberá ser ajustado a la cantidad de medicamento que se administró al animal.
        .col-md-4
          figure
            img(src='@/assets/curso/tema6-img39.png')

      .row
        .col-md-4.mb-4.mb-md-0
          figure
            img(src='@/assets/curso/tema6-img40.png')
        .col-md-7
          p.mb-0 En el caso de la carne, el tiempo de retiro debe ser el transcurrido entre la última aplicación de un medicamento veterinario a un animal y el momento de sacrificio de este para consumo humano.

      .row
        .col-md-7.mb-4.mb-md-0
          p.mb-0 En cuanto a la leche, los huevos y la miel el tiempo de retiro hace referencia al periodo durante el cual debe descartarse la leche, los huevos o la miel, esto para que los residuos de medicamento y/o sus metabolitos, alcancen niveles de inocuidad aceptados internacionalmente.
        .col-md-4
          figure
            img(src='@/assets/curso/tema6-img41.png')

    Separador

  .container.tarjeta.tarjeta--gris-especial.p-4.p-md-5.py-0.py-md-0.no-border.top-left.top-right.bottom-left.bottom-right

    #t_6_6.titulo-segundo.color-secundario
      h2 6.6  Notificación de efectos adversos

    p.mb-5 Las notificaciones o denuncias de casos que se presentan en los animales con sintomatología compatible o atribuible a enfermedades de notificación oficial según Resolución ICA 3714 del 2015, debe realizarse en las oficinas del Instituto Colombiano Agropecuario – ICA, las personas que se encuentran en la obligación de realizar esta acción son:

    .row
      .col-lg-3
        figure
          img(src="@/assets/curso/tema6-img31.svg")
      .col-lg-9
        ol.lista-ol--cuadro
          li.mb-2
            .lista-ol--cuadro__vineta
              span 1
            | Personas responsables, encargados o propietarios de los animales afectados, ya sea en grandes, medianas o pequeñas producciones.
          li.mb-2
            .lista-ol--cuadro__vineta
              span 2
            | Los médicos veterinarios, médicos veterinarios zootecnistas o profesionales en el área que atiendan producciones o presten asistencia técnica ya sea pública o privada.
          li.mb-2
            .lista-ol--cuadro__vineta
              span 3
            | Cualquier autoridad local, regional o nacional.
          li.mb-2
            .lista-ol--cuadro__vineta
              span 4
            | Responsables o encargados de los laboratorios diagnósticos veterinarios públicos o privados.
          li.mb-0
            .lista-ol--cuadro__vineta
              span 5
            | Cualquier persona con conocimiento de aves enfermas o aparentemente afectadas por enfermedades de notificación.

    Separador

  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.py-0.py-md-0.no-border.top-left.top-right.bottom-left.bottom-right

    #t_6_7.titulo-segundo.color-secundario
      h2 6.7  Guía sanitaria de movilización interna

    .row.mb-5
      .col-md-8.col-lg-9
        p.mb-5 Para garantizar las condiciones de salubridad y seguridad de los animales, el ICA diseñó un formato denominado Guía Sanitaria de Movilización Interna (GSMI). Este documento contiene información sobre el lugar de origen de los animales y las condiciones sanitarias en las que se entregan los animales; esto último con el fin de evitar propagación de enfermedades. En este formato se consignan datos como número de animales, género, predio de procedencia, destino final (transporte a otro predio o sacrificio), registro de vacunación, ruta de transporte, destino final.
        .cajon.color-primario.p-4.mb-4
          p.mb-0 Para que el ICA pueda emitir el aval para la guía de movilización, es necesario cumplir con los siguientes requisitos: que no haya presencia de focos de enfermedades en el predio, que este se encuentre registrado oficialmente ante el ICA, registro de vacunación vigente, inspecciones clínicas a los animales, registro de cuarentenas.

      .col-md-4.col-lg-3
        figure
          img(src="@/assets/curso/tema6-img32.svg")

    p.mb-5 Es de aclarar que esta guía solamente es válida para un solo vehículo y para un solo trayecto y aplica para la fecha autorizada. Sin embargo, un solo vehículo podrá transportar animales con diferentes GSMI, de diferentes orígenes y con diferentes destinos y se debe cumplir con los siguientes requisitos:

    .row.justify-content-center.mb-5
      .col-md-10
        .row.mb-lg-5.gx-5
          .col-lg-6.mb-md-0.d-flex
            .row.align-items-center.border-especial.top.bottom.py-4
              .col-2
                figure
                  img(src="@/assets/curso/tema6-img33.svg")
              .col-9.offset-1
                p.mb-0 Que el origen y el destino cuenten con igual condición sanitaria en cuanto a las enfermedades de control oficial y se encuentre dentro de las mismas zonificaciones declaradas por el ICA.
          .col-lg-6.mb-md-0.d-flex
            .row.align-items-center.border-especial.top.bottom.py-4
              .col-2
                figure
                  img(src="@/assets/curso/tema6-img34.svg")
              .col-9.offset-1
                p.mb-0 Que se identifiquen los lugares de origen y de destino en la ruta para la movilización de animales.
        .row.gx-5.mb-5
          .col-lg-6.mb-4.mb-md-0.d-flex
            .row.align-items-center.border-especial.bottom.py-4
              .col-2
                figure
                  img(src="@/assets/curso/tema6-img35.svg")
              .col-9.offset-1
                p.mb-0  Que los lugares de origen y destino no tengan requisitos sanitarios especiales para autorizar la movilización o para obtener la GSMI.
          .col-lg-6.mb-4.mb-md-0.d-flex
            .row.align-items-center.border-especial.bottom.py-4
              .col-2
                figure
                  img(src="@/assets/curso/tema6-img36.svg")
              .col-9.offset-1
                p.mb-0 Que las GSMI expedidas se encuentren vigentes dentro del tiempo autorizado para la movilización de los animales.

        p.mb-5 La expedición dela GSMI se puede expedir de dos formas:

        .tabla-a.color-acento-contenido.table-especial-cuerpo.mb-5
          table
            thead
              tr
                th 1.Presencial en la oficina local del ICA o convenio:
                th 2.En línea, a través de su plataforma Sigma:
            tbody
              tr.color-acento-contenido
                td
                  p.mb-0.p-4 Paso 1: Tener registrado el predio ante el ICA.
                    br
                    br
                    | Paso 2: Presentar la cédula de ciudadanía del titular de los animales o del apoderado.
                    br
                    br
                    | Paso 3: Presentar soporte de pago de la GMSI.
                    br
                    br
                    | Paso 4: Informar el destino de la movilización, número de animales, edad y especie a movilizar.
                    br
                    br
                    | Paso 5: Informar el nombre del conductor y datos del vehículo.
                    br
                    br
                    | Paso 6: Firmar recibo de satisfacción de la GSMI.

                td
                  p.mb-0.p-4 Paso 1: Ingresar al enlace <a href="https://www.ica.gov.co/servicios_linea/sigma/manuales.aspx" target='_blank'>https://www.ica.gov.co/servicios_linea/sigma/manuales.aspx</a> para descargar el acta de confidencialidad de usuarios y obtener información adicional.
                    br
                    br
                    | Paso 2: Diligenciar el acta de confidencialidad.
                    br
                    br
                    | Paso 3: Enviar el acta escaneada y el documento de identificación al correo electrónico mesadeayuda.sigma@ica.gov.co.
                    br
                    br
                    | En un tiempo estimado de 24 horas, recibirá a vuelta de correo el usuario y contraseña para poder ingresar a Sigma en línea y continuar con el trámite para expedir la guía de movilización.

</template>

<script>
import TabsSpecial from '../components/TabEspecial'
export default {
  name: 'Tema6',
  components: {
    TabsSpecial,
  },
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
  methods: {
    openImage(link) {
      window.open(link, '_blank')
    },
  },
}
</script>

<style lang="sass"></style>
