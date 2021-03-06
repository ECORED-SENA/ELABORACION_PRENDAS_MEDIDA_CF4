<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Fundamentos para el diseño de patrones básicos

    .row.justify-content-center
      .col-lg-10
        p.mb-3 Los patrones básicos son el producto seguido a la aplicación de las medidas anatómicas, por consiguiente, es un calco del cuerpo; sin embargo, estos patrones no pueden ser utilizados para ser cortados de forma inmediata en tela o utilizados para elaborar una prenda, ya que antes deben recibir adaptaciones (desahogos, amplitudes, cortes, etc.) para proceder a ser utilizados en producción. De su calidad dependerá la estabilidad dimensional del patrón y el buen calce de la prenda una vez confeccionada. 

        p.mb-5 Los patrones base o básicos se crean según el tipo de prenda como se muestra en la siguiente figura.

        
        p.BorTit Figura 1, División de moldes según el tipo de prenda
        figure.mb-5
          img.img-a(src='@/assets/curso/tema_1/img_1.png', alt='División de moldes según el tipo de prenda')
          figcaption Nota: SENA (2021)

    .titulo-segundo
      #t_1_1.h2 1.1 Trazo de falda básica

    p.mb-3 Para comenzar el proceso de construcción de moldes se recomienda iniciar con patrones o levantamientos más simples; la falda básica es el primer estilo porque es la prenda más simple; a través de estas líneas se asimila la utilización correcta de cada regla de costura, obteniendo así una mayor seguridad para manejar los siguientes estilos de las medidas a utilizar para el trazo de la falda: contorno de cintura, contorno de cadera y largo de falda.

    p.mb-5 Analizar la tipología de la falda a desarrollar es importante para determinar qué medida de largo se necesita para generar el rectángulo de inicio para el levantamiento del molde. De acuerdo con su longitud, la falda puede ser:  minifalda, maxi falda, hasta la rodilla y hasta el suelo. Por otro lado, la circunferencia de la cintura puede ser tan baja como por debajo del ombligo y tan alta como por encima de la cintura. 

    .row.mb-5
      .col-lg-8
        p.BorTit Figura 2, Longitud de falda
        figure
          img(src='@/assets/curso/tema_1/img_2.png', alt='Longitud de falda')
          figcaption Nota. Carrera de diseño y gestión de moda (2015)
      .col-lg-4
        p.BorTit Figura 3, Circunferencia de la cintura
        figure
          img.alt_img(src='@/assets/curso/tema_1/img_17.png', alt='Circunferencia de la cintura')
          figcaption Nota. Carrera de diseño y gestión de moda (2015)

    

    p.mb-5 Para hacer el trazado de este tipo de falda se debe tomar como punto de partida las medidas anatómicas con precisión, no deben sumar centímetros de más, por ello, se recomienda seguir con atención los pasos del manual de patronaje básico e interpretación de diseños que se relaciona a continuación, pues el básico inferior de falda siempre se trabaja partiendo de un rectángulo e identificando los siguientes puntos:

    .row.mb-5
      .col-lg-6
        ul.lista-ul--color.mb-5
          li 
            i.fas.fa-angle-right
            | Parte superior (cintura) – línea superior.
          li 
            i.fas.fa-angle-right
            | Parte inferior (rodilla) – línea inferior. 
          li 
            i.fas.fa-angle-right
            | Parte derecha – posterior.
          li 
            i.fas.fa-angle-right
            | Parte izquierda – delantero. 

        a.anexo(:href="obtenerLink('/downloads/Manual_patronaje_basico_interpretacion_disenos.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p.my-0 #[strong Anexo]. Manual de patronaje básico e interpretación de diseños
            p.my-0 Los puntos de referencia para el trazado de las faldas, p. 13-17.
            p Los patrones básicos para hacer una falda a una pinza y a dos pinzas en escala, p. 31-32.

      .col-lg-6
        figure
          img.img-a(src='@/assets/curso/tema_1/img_3.png')

    .jumbo_1.mb-5
      p.mt-2.text-center De igual manera, se recomienda que consulte el video base inferior falda femenino que le permitirá conocer el paso a paso para realizar el básico de una falda.
    p.BorTit Base inferior falda femenino
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/wl5EjrLU-8Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video explicativo con la información sobre el paso a paso para realizar el básico de una falda.

    p.text-center.mb-5 A partir de la información consultada en el manual y en el video explicativo, a continuación, se presentan los pasos detallados para realizar la base de falda. 

    h2.text-center.mb-5 Conozca los pasos detallados para realizar la base de falda  

    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-8
        TabsB
          .py-4.py-md-5.tab1(titulo="PASO 1")

            .nav-bg.p-5
              p 
                strong Trazar un rectángulo con las medidas correspondientes a la talla: 
              ul.lista-ul.mb-3
                li 
                  i.lista-ul__vineta
                  | #[strong Ancho ]: contorno de cadera / 2.
                li 
                  i.lista-ul__vineta
                  | #[strong Largo ]: largo de falda o rodilla.

          .py-4.py-md-5(titulo="PASO 2")
            .nav-bg.p-5
              p
                strong Localizar las líneas:
              ul.lista-ul.mb-3
                li 
                  i.lista-ul__vineta
                  | #[strong Largos]: cintura y rodilla, entre cintura y rodilla aparece la línea de altura de cadera.
                li 
                  i.lista-ul__vineta
                  | #[strong Anchos]: centro frente y centro atrás, la división entre delantero y posterior es costado.

            
          .py-4.py-md-5(titulo="PASO 3")
            .nav-bg.p-5
              p 
                strong Identificar cada uno de los puntos de referencia en la parte posterior:
              ul.lista-ul.mb-3
                li 
                  span.lista-ul__vineta #[strong Cintura: ]
                    | en la medida de cintura se aumenta los centímetros de pinza. Esta puede variar dependiendo de diferentes factores como la silueta, el tipo de cuerpo y la edad.
                li 
                  span.lista-ul__vineta #[strong Pinza: ]
                    | la pinza se compone por largo y ancho, se sugiere trabajar un ancho de 3 cm. Pero cuando se realiza sobre medida también se puede obtener con ¼ busto – ¼ cintura para obtener el ancho de pinza.
                li 
                  span.lista-ul__vineta #[strong Ancho de pinza: ]
                    | se compone por primer y segundo lado de pinza, por lo general se suele distribuir el ancho de pinza a lado y lado del vértice, es decir, en este caso que la pinza es de 2 cm, la distribución se hace desde el vértice de pinza 1 cm a cada lado.
                li 
                  span.lista-ul__vineta #[strong Largo de pinza: ]
                    |  el largo de pinza se encuentra estandarizada en el manual o se puede sacar por medida deducida.
          
          .py-4.py-md-5(titulo="PASO 4")
            .nav-bg.p-5
              p 
                strong Identificar la desnivelación de la cintura: 
              ul.lista-ul.mb-3
                li 
                  i.lista-ul__vineta
                  | En el punto de cintura costado posterior se debe subir 1 cm, con el fin de mantener los desniveles de cintura.
                li 
                  i.lista-ul__vineta
                  | En el punto de cintura centro atrás se debe bajar 1 cm, con el fin de favorecer la curva de cintura, frente al volumen de los glúteos.
          
          .py-4.py-md-5(titulo="PASO 5")
            .nav-bg.p-5
              p #[strong Identificar la separación de busto o vértice de pinza]: desde los básicos se suelen identificar los puntos de vértice de pinza. 
          
          .py-4.py-md-5(titulo="PASO 6")
            .nav-bg.p-5
              p #[strong Trazar la curva de cadera]: unir desde el punto de cintura costado en línea curva, hasta la línea base de costado, suavizando la unión.

          .py-4.py-md-5(titulo="PASO 7")
            .nav-bg.p-5
              p #[strong Marcar o repisar] el trazo de la falda base posterior, centro atrás, cintura, pinza, costado y  largo.

          .py-4.py-md-5(titulo="PASO 8")
            .nav-bg.p-5
              p #[strong Identificar] cada uno de los puntos de referencia en la parte delantera, se debe tener en cuenta los mismos pasos de la parte posterior.

    .titulo-segundo
      #t_1_2.h2 1.2 Trazo de faldas rotondas 

    .row.justify-content-center.mb-5
      .col-lg-8
        p Las faldas rotondas son también conocidas como las faldas plato, debido a que el patrón de esta tipología parte de una circunferencia. Las faldas rotondas se hicieron famosas en los años 50 con el inicio del estilo new look del famoso diseñador Christian Dior.

        p.mb-5 En la siguiente figura puede apreciar los tipos de faldas rotondas.

        p.BorTit Figura 4, Tipos de faldas rotondas
        figure.mb-5
          img.img-a(src='@/assets/curso/tema_1/img_4.png', alt='Tipos de faldas rotondas')
          figcaption Nota. Confecciones Linda (2019)

        p De igual forma, se recomienda que consulte el video trazo de faldas rotondas que le permitirá conocer cómo realizar este trazo.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/NxZQL369p9Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Tipos de faldas rotondas

    .row.justify-content-center.mb-5 
      .col-lg-10
        p #[strong Modificación de básicos de falda:] para obtener un buen resultado del análisis de una prenda se debe tener en cuenta la tipología, la tela, las características del diseño, los cortes, el sistema de cierre y los complementos. El propósito del ejercicio es poder comparar métodos de implementación básicos, aplicando el mismo tipo a diferentes tipos de diseños.

        p A continuación, se presenta el video trazo de falda y modificación de básicos de falda a través del cual podrá conocer sobre el trazo de faldas y modificación de básicos de faldas.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/xtyPQh3vtuc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: trazo de falda y modificación de básicos de falda

    .row.mb-5
      .col-lg-4
        figure
          img.img-a(src='@/assets/curso/tema_1/img_5.png', alt='Longitud de falda')

      .col-lg-8
        p.mb-5 De igual manera, se recomienda que consulte el manual de patronaje básico e interpretación de diseños para que conozca las agrupaciones del patrón partiendo del diseño de faldas.

        a.anexo(:href="obtenerLink('/downloads/Manual_patronaje_basico_interpretacion_disenos.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p.my-0 #[strong Anexo]. Manual de patronaje básico e interpretación de diseños.
            p Las agrupaciones del patrón partiendo del diseño de faldas, p. 33-38.

    .titulo-segundo
      #t_1_3.h2 1.3 Trazo de base superior femenina    

    p Es uno de los pilares de la moldería porque constituye el molde que se debe realizar para definir la intención con la cual se realiza la prenda. El manejo de volúmenes es uno de los principales factores diferenciadores en el desarrollo de prendas, siendo las pinzas y sistemas de ajustes los protagonistas de este proceso. Se debe tener en cuenta que sin importar la línea que se trabaje, la metodología del manual y los pasos, siempre serán los mismos, este orden secuencial le permite tener una mayor y mejor apropiación de la metodología. 

    p.mb-5 Para realizar este trazo se debe tener en cuenta el volumen de la prenda, las medidas a utilizar y los pasos para el trazo de la base superior femenina. 

    .row.justify-content-center.mb-5
      .col-lg-6
        .jumbo_2
          h2.text-center Trazo de base superior femenina

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      div(titulo="Volumen de la prenda")
        p #[strong Existen] prendas más grandes que el cuerpo, iguales o más pequeñas como las elaboradas en tejidos de punto o con telas licradas. La diferencia entre la prenda y el cuerpo que la viste recibe el nombre de #[strong desahogo], el mayor o menor desahogo condiciona el volumen de la prenda. Debe tenerse en cuenta que se debe mantener constante el desahogo de una prenda en todas las tallas del mismo diseño. 

        p.mb-5 A continuación, se muestran los valores de desahogo estimados según el tipo de prenda y volumen deseado.

        .tabla-b.color-acento-contenido.mb-5
          table
            thead
              tr.tabla-b__header.text-white
                th Prenda
                th Estrecho
                th Ajustada
                th Normal
                th Ancha
                th Muy ancha
              tr 
                th Blusa
                td.text-center 2 cm
                td.text-center 4 cm
                td.text-center 6 cm
                td.text-center 8 cm
                td.text-center 10 cm
              tr
                th Vestido
                td.text-center 4 cm
                td.text-center 6 cm
                td.text-center 8 cm
                td.text-center 10 cm
                td.text-center 12 cm
              tr
                th Falda
                td.text-center 0 cm
                td.text-center 1 cm
                td.text-center 2 cm
                td.text-center 6 cm
                td.text-center 8 cm
              tr
                th Pantalón
                td.text-center 0 cm
                td.text-center 1 cm
                td.text-center 2 cm
                td.text-center 4 cm
                td.text-center 6 cm
              tr
                th Chaqueta
                td.text-center 4 cm
                td.text-center 6 cm
                td.text-center 8 cm
                td.text-center 10 cm
                td.text-center 12 cm
              tr
                th Chaquetón
                td.text-center 6 cm
                td.text-center 8 cm
                td.text-center 10 cm
                td.text-center 12 cm
                td.text-center 14 cm
              tr
                th Abrigos
                td.text-center 8 cm
                td.text-center 10 cm
                td.text-center 12 cm
                td.text-center 14 cm
                td.text-center 16 cm

      
        
      div(titulo="Volumen del tejido")
        p.mb-5 En función del volumen del tejido los anteriores valores pueden ser ajustados de la siguiente manera, los cuales son aplicados al contorno.

        .tabla-b.color-acento-contenido.mb-5
          table
            thead
              tr.tabla-b__header.text-white
                th Muy fino
                th Fino
                th Normal
                th Grueso
                th Muy Grueso
              tr.text-center
                td -2 cm
                td -1 cm
                td 0 cm
                td +2 cm
                td +4 cm

      div(titulo="Pasos para el trazo de la base superior")
        p.mb-5 Cuando se habla de la base superior se hace referencia a la copia de la horma del cuerpo, partiendo del cuello hasta la cintura, dicha base será la plantilla que se adecuará para convertirse en:
        figure
          img.img-a(src='@/assets/curso/tema_1/img_6.png', alt='Pasos para el trazo de la base superior')

    p.mb-5.text-center A continuación, se relacionan las medidas a utilizar para el trazo de la base. 

    figure.mb-5
      img.img-a(src='@/assets/curso/tema_1/img_7.svg', alt='Medidas a utilizar para el trazo de la base') 

    .row.justify-content-center.mb-5
      .col-lg-6
        p.mb-5 De igual forma, se recomienda que consulte el manual de patronaje básico e interpretación de diseños para que conozca el patrón base superior femenino.

        a.anexo(:href="obtenerLink('/downloads/Manual_patronaje_basico_interpretacion_disenos.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p.my-0 #[strong Anexo]. Manual de patronaje básico e interpretación de diseños.
            p Patrón base superior femenino, p. 20-25.

    .row.justify-content-center.mb-5
      .col-lg-8
        .jumbo_3
          p.text-center.text-white A continuación, se relacionan los pasos para conocer la base posterior superior femenina. 

     

    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-8
        TabsB
          .py-4.py-md-5.tab1(titulo="PASO 1")

            .nav-bg.p-5
              p 
                strong Trazar un rectángulo con las medidas correspondientes del cliente: 
              ul.lista-ul.mb-3
                li 
                  i.lista-ul__vineta
                  | #[strong Ancho ]: contorno de busto / 4.
                li 
                  i.lista-ul__vineta
                  | #[strong Largo ]: largo de talle posterior.

          .py-4.py-md-5(titulo="PASO 2")
            .nav-bg.p-5
              p Identificar en el rectángulo la línea de cuello, cintura centro frente y centro atrás.

            
          .py-4.py-md-5(titulo="PASO 3")
            .nav-bg.p-5
              p 
                strong Identificar cada una de las líneas:
              ul.lista-ul.mb-3
                li 
                  span.lista-ul__vineta #[strong Largos]: 
                    | para identificar la profundidad del escote es necesario marcar desde el punto de cintura – centro atrás hacia la línea de cuello, la medida de centro atrás.
                li 
                  span.lista-ul__vineta #[strong Línea de profundidad de sisa]: 
                    | se debe tomar la medida de centro atrás y dividirla en dos partes iguales, de la mitad hacia la cintura bajar 2 cm. 
                li 
                  span.lista-ul__vineta #[strong Anchos]: 
                    | se mide desde el centro del cuello hasta donde se desee que abra el escote en el lateral, corresponde a 1/5 contorno de cuello.
                li 
                  span.lista-ul__vineta #[strong Ajuste de fórmula]:
                    | en la forma 1/5 de contorno de cuello + 0.3, a nivel industrial se busca dejar siempre medidas que se encaran del mismo ancho, esto con el fin de facilitar los procesos de producción; sin embargo, al dejar un escote más ancho que otro se otorga mayor ajuste al cuerpo, mejor horma e incrementa los costos de producción. Marcar la curva de escote posterior con un curvígrafo.

          
          .py-4.py-md-5(titulo="PASO 4")
            .nav-bg.p-5
              p 
                strong Medir hombro: en el hombro se toman dos medidas: 
              ul.lista-ul.mb-3
                li 
                  span.lista-ul__vineta #[strong Caída de hombro]:   
                    | 4 cm a nivel industrial y en cualquier talla.
                li 
                  span.lista-ul__vineta #[strong Largo de hombro]: 
                    | medida asignada en el cuadro de tallas (varía por talla).
          
          .py-4.py-md-5(titulo="PASO 5")
            .nav-bg.p-5
              p #[strong Definir ancho de espalda]: se debe tomar la mitad de ancho de espalda y marcar por la línea de profundidad de sisa, desde centro atrás, hacia el costado. 
          
          .py-4.py-md-5(titulo="PASO 6")
            .nav-bg.p-5
              p #[strong Definir altura de ancho de espalda]: para identificar la altura de ancho de espalda se debe identificar la mitad desde la línea de profundidad de sisa hasta el escote por el centro atrás. Para marcar la curva de sisa desde el punto largo del hombro, por la línea de ancho de espalda hasta línea de profundidad de sisa, identifique la mitad. De la mitad hacia arriba, una en línea recta. De la mitad hacia abajo, una en línea curva.

          .py-4.py-md-5(titulo="PASO 7")
            .nav-bg.p-5
              p #[strong Realizar pinza]: la cual depende de la separación de busto, para poder ubicar el vértice de pinza se debe identificar la mitad de separación de busto y marcar por la línea de profundidad de sisa, desde el centro hacia el costado.

          .py-4.py-md-5(titulo="PASO 8")
            .nav-bg.p-5
              p #[strong Definir desniveles de cintura]: en el punto de costado cintura posterior, entrar 2 cm, desde esos 2 cm prolongar la medida de costado.

    .row.justify-content-center.mb-5
      .col-lg-8
        .jumbo_3
          p.text-center.text-white La siguiente infografía relaciona los pasos detallados para realizar la base delantera superior femenina.


    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-8
        TabsB
          .py-4.py-md-5.tab1(titulo="PASO 1")

            .nav-bg.p-5
              p 
                strong Trazar un rectángulo con las medidas correspondientes del cliente:  
              ul.lista-ul.mb-3
                li 
                  i.lista-ul__vineta
                  | #[strong Ancho ]: contorno de busto/4. 
                li 
                  i.lista-ul__vineta
                  | #[strong Largo ]: largo de talle posterior.

          .py-4.py-md-5(titulo="PASO 2")
            .nav-bg.p-5
              p Marcar líneas desde la línea de profundidad de sisa, mitad hacia arriba, mitad hacia abajo.

            
          .py-4.py-md-5(titulo="PASO 3")
            .nav-bg.p-5
              p Trazar el rectángulo por el que se va a trabajar en la parte delantera e identificar o bautizar cada una de las líneas. 

          
          .py-4.py-md-5(titulo="PASO 4")
            .nav-bg.p-5
              p Identificar en el rectángulo la línea de cuello, cintura, centro frente costado.
              
          .py-4.py-md-5(titulo="PASO 5")
            .nav-bg.p-5
              p 
                strong Identificar cada una de las líneas que divide el cuerpo y por las que va a pasar la base.

              ul.lista-ul.mb-3
                li 
                  span.lista-ul__vineta #[strong Largos]: 
                    | Largos: para identificar la profundidad del escote es necesario marcar desde el punto de cintura – centro frente hacia la línea de cuello la medida de centro frente.
                li 
                  span.lista-ul__vineta #[strong Ancho de escote]: 
                    | el ancho de escote sale por fórmula, que corresponde a 1/5 contorno de cuello.
                li 
                  span.lista-ul__vineta #[strong Ajuste de fórmula]: 
                    | en la forma 1/5 de contorno de cuello – 0.5 cm a nivel industrial se busca dejar siempre medidas que se encaran del mismo ancho, esto con el fin de facilitar los procesos de producción; sin embargo, al dejar un escote más ancho que otro se otorga mayor ajuste al cuerpo, mejor horma e incrementa los costos de producción. Marcar la curva de escote delantero con curvígrafo.
          
          .py-4.py-md-5(titulo="PASO 6")
            .nav-bg.p-5
              p #[strong Medir hombro]: se toman dos medidas, caída de hombro 4 cm a nivel industrial y largo de hombro.

          .py-4.py-md-5(titulo="PASO 7")
            .nav-bg.p-5
              p #[strong Definir ancho de pecho]: para identificar el ancho de pecho se debe tomar la mitad del ancho de la espalda y marcar por la línea de profundidad de la sisa, desde el centro frente, hacia el costado. 

          .py-4.py-md-5(titulo="PASO 8")
            .nav-bg.p-5
              p #[strong Definir la altura de ancho de espalda]: para identificar la altura de ancho de espalda se debe identificar la mitad desde línea de profundidad de sisa hasta el escote por el centro atrás.

          .py-4.py-md-5(titulo="PASO 9")
            .nav-bg.p-5
              p #[strong Marcar la curva de sisa]: desde el punto largo de hombro, por la línea de ancho de espalda hasta la línea de profundidad de sisa, identifique la mitad.
              ul.lista-ul.mb-3
                li 
                  i.lista-ul__vineta
                  | De la mitad hacia arriba, una en línea recta.
                li 
                  i.lista-ul__vineta
                  | De la mitad hacia abajo, una en línea curva.

          .py-4.py-md-5(titulo="PASO 10")
            .nav-bg.p-5
              p #[strong Separar busto]: no solo se identifica por separación de busto, si no que depende de la medida de altura del busto.

          .py-4.py-md-5(titulo="PASO 11")
            .nav-bg.p-5
              p #[strong Definir la altura de busto]: bajar 5 cm por vértice de pinza.

          .py-4.py-md-5(titulo="PASO 12")
            .nav-bg.p-5
              p Unir cada uno de los puntos referentes al delantero e identificar la parte delantera y la parte posterior.

    .row.justify-content-center.mb-5
      .col-lg-8
        .tarjeta--container.row.mb-5
          .col-md.tarjeta--boton.color-acento-contenido.p-5
            .row.justify-content-center.mb-4
              .col-6
                figure
                  img.img-a(src='@/assets/curso/tema_1/img_8.svg', alt='Texto que describa la imagen')
              
            .h2.text-center Traslado de pinzas
            p Los patrones base o básicos en su gran mayoría tienen pinzas, pero estas no son necesarias en todos los modelos o diseños, para resolver lo expuesto se realiza un proceso de traslado por medio de giros rotativos también conocidos como pivoteos, que permiten cambiar la pinza de posición o ubicarla en algún corte para que simplemente salga del molde. Se debe tener presente que este pivote parte de un punto fijo que se ubica sobre la altura del busto y en medio de la separación del busto (en el pezón). 

          .col-md.tarjeta--boton.color-acento-contenido.p-5
            .row.justify-content-center.mb-4
              .col-6
                figure
                  img.img-a(src='@/assets/curso/tema_1/img_9.svg', alt='Texto que describa la imagen')
              
            .h2.text-center Pinza correctiva de talle
            p En el momento que se unen por los básicos delantero y posterior por la línea de la cintura se evidencia el desnivel anatómico entre estos, es de aquí que surge esta pinza como una marca de referencia principal para generar volúmenes o ajustes sobre el cuerpo. Puede ser trasladada o llevada a diferentes puntos del cuerpo, facilitando acentuar volúmenes, generar siluetas o estructuras que permiten modificar diseños; según la interpretación queda invisible o visible a propósito. 

    .row.justify-content-center.mb-5
      .col-lg-8
        .row.align-items-center
          .col-lg-5
            figure
              img(src='@/assets/curso/tema_1/img_10.png', alt='Texto que describa la imagen')
          .col-lg-7
            ul.lista-ul--color
              li 
                i.fas.fa-angle-right
                | Las pinzas pueden ser transferidas o desviadas a cualquier dirección alrededor del punto de busto (punto giratorio) sin afectar el tamaño, ni el entalle del patrón.

              li 
                i.fas.fa-angle-right
                | El exceso de la pinza, es decir, el espacio entre lados de la pinza puede ser utilizado como recogidos, pliegues, pinzas semicosidas o en los cortes de diferentes estilos o diseños.

            p.mb-5 Todas las pinzas deben terminar antes del punto de busto (punto giratorio), nunca deben traspasar dicho punto. 

        p A continuación, se podrán conocer algunas #[strong técnicas de transformación de las prendas]:

        ol.lista-ol--cuadro.mb-5
          li 
            .lista-ol--cuadro__vineta
              span 1
            p #[strong Cortar y unir]: este método requiere cortar el patrón base para luego unir las partes con la reubicación de la pinza.
          li 
            .lista-ol--cuadro__vineta
              span 2
            p #[strong Pivoteo (girar)]: este método no requiere cortar el patrón básico, sino girarlo a través del punto de busto transfiriendo de esta manera la pinza. Tal como se muestra en la imagen, existen varios puntos de traslados de pinzas, como lo son:

        p.BorTit Figura 5, Puntos de traslado de pinza
        figure.mb-3
          img(src='@/assets/curso/tema_1/img_11.svg', alt='Puntos de traslado de pinza')
          figcaption Nota. Carrera de diseño y gestión de moda (2015)


    .row.justify-content-center.mb-3
      .col-lg-6
        p Después de tener en cuenta los puntos de traslado de las pinzas, es importante conocer estos traslados, pero en la base, tal como se muestra a continuación.

    
    .row.justify-content-center.mb-3
      .col-lg-8
        p.BorTit Figura 6, Traslados de pinza en base 
        figure.mb-3
          img(src='@/assets/curso/tema_1/img_12.svg', alt='Traslados de pinza en base')
          figcaption Nota. Carrera de diseño y gestión de moda (2015)

    .row.justify-content-center.mb-3
      .col-lg-6
        p Además, se recomienda que consulte el video explicativo sobre cómo se hacen los traslados de pinza correctiva de talles.

    p.BorTit Traslados de pinza correctiva de talles
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/encNXGtE15Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      

    .titulo-segundo
      #t_1_4.h2 1.4 Análisis y trazo de sistema de ajuste

    .row.mb-5
      .col-lg-4
        img(src='@/assets/curso/tema_1/img_13.png')
      .col-lg-8
        p Dentro del desarrollo de moldes y patrones se hace indispensable el manejo de pinzas como sistema de ajuste o como insumo principal para el manejo de volúmenes, las pinzas en femenino son un punto de partida primordial y específico, que es necesario comprender desde la base funcional estructural y matemática.

        p Para comprender el funcionamiento de las pinzas se trabajará únicamente la parte superior femenina, contemplando la circunferencia y el volumen del busto, de igual manera el contorno de cintura y el contorno de cadera, cada uno de estos contornos maneja características como volúmenes más protuberantes de los #[strong tops] o los #[strong bottoms] y punto de unión o encuentro entre la división del cuerpo.

        p En el manejo de pinzas únicamente se trabajará con los contornos relevantes o que se toman como punto de partida para la construcción de básicos, para ello se tiene en cuenta: el contorno de busto, el contorno de cintura y el contorno de cadera. 

    p Sin importar el tipo de prenda, los desahogos o la interpretación, las pinzas como sistema de ajuste siempre se trabajarán sobre esos contornos, debido a que son los contornos con los que se trabaja la base o el básico. 

    p.mb-5 A continuación, se relacionan las orientaciones que se deben tener en cuenta para definirlas: 

    .row.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema_1/img_14.svg' alt='AvatarTop')
          .tarjeta.tarj_color
            .p-4
              .h2.text-center Prendas superiores ajuste por cintura
              p.text-center Se mide el contorno de busto (medida base) menos el contorno de cintura (medida más pequeña a ajustar).

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema_1/img_15.svg' alt='AvatarTop')
          .tarjeta.tarj_color
            .p-4
              .h2.text-center Prendas superiores ajuste por cadera
              p.text-center Se mide el contorno de busto (medida base) menos el contorno de cadera (medida más protuberante).

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema_1/img_16.svg' alt='AvatarTop')
          .tarjeta.tarj_color
            .p-4
              .h2.text-center Prendas inferiores ajuste por cintura
              p.text-center Se mide el contorno de cadera (medida base) menos el contorno de cintura (medida más pequeña a ajustar). 

    .row.justify-content-center.mb-5
      .col-lg-8
        p.text-center Con el fin de que conozca cómo se realiza el trazo de sistemas de ajuste de pinzas y cortes consulte el video análisis y trazo de sistema de ajuste pinzas y cortes que aparece a continuación.

    p.BorTit Análisis y trazo de sistema de ajuste pinzas y cortes.
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/Tq_3F32nynw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      

  
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
