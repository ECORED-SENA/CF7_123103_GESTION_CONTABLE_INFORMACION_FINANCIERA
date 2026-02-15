<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Instrumentos de patrimonio
    .d-flex.flex-wrap
      .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
        p.mb-4 Un instrumento de patrimonio es un negocio respaldado por un contrato que pone de manifiesto una participación residual en los activos de una entidad después de deducir todos los pasivos.
        .row.align-items-center.py-2.mx-0.mb-4(style="background-color: #FEEAD4")
          .col-auto
            figure(data-aos="fade-up")
              img.mb-4.mb-lg-0(src="@/assets/curso/tema2/img-2.svg", alt="" style="max-width: 81px").m-auto
          .col-xl
            p.mb-0 Algunos ejemplos de instrumentos de patrimonio, son las acciones ordinarias, ciertos tipos de acciones preferentes, así como, las opciones u otro tipo de derechos o bonos para la suscripción o compra de acciones ordinarias de la empresa.
        p.mb-4 A continuación, se relaciona un ejemplo específico de ello:
          br
          br
          |Una obligación (contrato) que será cancelada por la entidad entregando o recibiendo una cantidad acordada de sus instrumentos de patrimonio propio a cambio de un importe fijo en efectivo o cualquier otro activo financiero será un instrumento de patrimonio.
      .mx-auto.col-md-8.col-lg-5.order-1.order-lg-2
        img(src="@/assets/curso/tema2/img-1.svg", alt="", style="max-width: 505px").mx-auto.mb-4.ps-lg-4  
    separador

    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1 Reconocimiento, medición, presentación, revelación
    
    .fondo-slider(style="background: linear-gradient(0deg, rgba(0,0,0,0) 30%, rgba(243,240,234,1) 30%, rgba(243,240,234,1) 80%, rgba(0,0,0,0) 100%);")
      .row.caja-text-img-tema1.align-items-center.mx-0.mb-0.py-3(style="background-color: #003F62")
        .col-xl-auto
          figure(data-aos="fade-up").d-none.d-xl-block
            img(src="@/assets/curso/tema1/img-1.png", alt="" style="max-width: 100px").m-auto
        .col-xl
          p.mb-0.text-white.fw-bold En el presente ítem se abordan conceptos que determinan el reconocimiento de los instrumentos de patrimonio; a su vez, presenta ejemplos que acompañan el proceso de aplicabilidad.
        
      .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
        .col
          h3 Reconocimiento
      
      p.mb-5 Una entidad reconocerá la emisión de acciones o de otros instrumentos de patrimonio cuando emita esos instrumentos y otra parte esté obligada a proporcionar efectivo u otros recursos a la entidad a cambio de éstos. (Pasivos y patrimonio 2009, s.f).

        .row.mb-5.m-0.ajuste-espacios-movil
          .col-lg-4.espacio__cajas_movil
            .ajuste-caja-text-bloque4.h-100.px-4(data-aos="flip-left" style="background-color: #CBE7E8")
              .col
                figure.mb-3
                  img(src='@/assets/curso/tema2/img-3.svg', alt='' style="max-width: 105px").m-auto
                p.text-center.fw-bold 01
                p.text-center Si los instrumentos de patrimonio se emiten antes de que la entidad reciba el efectivo u otros recursos, la entidad presentará el importe por cobrar como una compensación al patrimonio en su estado de situación financiera, no como un activo.
          .col-lg-4.espacio__cajas_movil
            .ajuste-caja-text-bloque4.h-100.px-4(data-aos="flip-left" style="background-color: #CBE7E8")
              .col
                figure.mb-3
                  img(src='@/assets/curso/tema2/img-3.svg', alt='' style="max-width: 105px").m-auto
                p.text-center.fw-bold 02
                p.text-center Si la entidad recibe el efectivo u otros recursos antes de que se emitan los instrumentos de patrimonio, y no se puede requerir a la entidad el reembolso del efectivo o de los otros recursos recibidos, la entidad reconocerá el correspondiente incremento en el patrimonio en la medida de la contraprestación recibida.
          .col-lg-4.espacio__cajas_movil
            .ajuste-caja-text-bloque4.h-100.px-4(data-aos="flip-left" style="background-color: #CBE7E8")
              .col
                figure.mb-3
                  img(src='@/assets/curso/tema2/img-3.svg', alt='' style="max-width: 105px").m-auto
                p.text-center.fw-bold 03
                p.text-center En la medida en que los instrumentos de patrimonio hayan sido suscritos, pero no emitidos y la entidad no haya todavía recibido el efectivo o los otros recursos, la entidad no reconocerá un incremento en el patrimonio.


      .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
        .col
          h3 Medición

    p.mb-5 Con los nuevos marcos normativos, es improbable que el patrimonio contable multiplicado por el porcentaje de participación represente una estimación fiable del valor razonable de una inversión en instrumento de patrimonio sin cotización pública.

    .d-flex.flex-wrap.mb-5
      .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
        p.mb-4 En periodos posteriores al reconocimiento inicial, y solo para algunos casos, por ejemplo, en inversiones patrimoniales de baja o ninguna bursatilidad, el valor determinado a partir de una remedición a valor razonable de todos los activos y pasivos de la entidad (patrimonio) podría representar una estimación fiable.
        
        p.mb-0.p-4(style="background-color: #FEEAD4") #[b Ejemplo:]
          br
          br
          |La sociedad Contable SAS, compra el primero de julio del año 0 un paquete de acciones del Banco de Bogotá, por valor de $130.000.000 y las clasifica como activos disponibles para la venta.
      .mx-auto.col-lg-5.order-1.order-lg-2
        img(src="@/assets/curso/tema2/img-4.svg", alt="", style="max-width: 505px").mx-auto.mb-4.ps-lg-4

    .row.align-items-center.mx-0.mb-5.py-0(style="background-color: transparent")
      .col-xl-auto
        figure(data-aos="fade-up").d-none.d-xl-block
          img(src="@/assets/curso/tema1/img-1.png", alt="" style="max-width: 100px").m-auto
      .col-xl
        p.mb-0 También compra opciones de venta que le dan derecho a vender el paquete de acciones por $130.000.000, el precio pagado por la opción es de $1.300.000.
          br
          br
          |A 31 de diciembre del año 0, el valor razonable del paquete de acciones es de $125.000.000 y el valor razonable de la opción es de $1.600.000.

    .row.fondo-slider.mb-5.ajuste-espacios-movil(:style="{'background-image': `url(${require('@/assets/curso/tema1/img-bg-table.png')})`, backgroundSize: 'cover'}")
      .ajuste-slider
        SlyderA(tipo="b")
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-12.col-lg-10.col-xl-9.mx-auto(data-aos="fade-right")
              p.fw-bold.text-center Reconocimiento inicial, compra del paquete de acciones
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 20.
                span Registro contable de inversión financiera en instrumentos de patrimonio
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Inversiones financieras a largo plazo en instrumentos de patrimonio
                      td.text-end $ 130.000.000,00
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Bancos
                      td.text-end -
                      td.text-end $ 130.000.000,00
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-12.col-lg-10.col-xl-9.mx-auto(data-aos="fade-right")
              p.fw-bold.text-center Reconocimiento inicial, compra de las opciones
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 21.
                span Reconocimiento de activos por instrumentos financieros derivados de cobertura a largo plazo
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Activos por derivados financieros a largo plazo, instrumentos de cobertura
                      td.text-end $ 130.000.000,00
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Bancos
                      td.text-end -
                      td.text-end $ 130.000.000,00
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-12.col-lg-10.col-xl-9.mx-auto(data-aos="fade-right")
              p.fw-bold.text-center Reconocimiento posterior a 31 de diciembre. Por la contabilización de la partida cubierta a valor razonable con cambios en resultados
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 22.
                span Reconocimiento de pérdida por desvalorización en inversiones financieras de largo plazo
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Pérdidas de disponibles para laventa
                      td.text-end $ 5.000.000,00
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Inversiones financieras a largo plazo en instrumentos de patrimonio
                      td.text-end -
                      td.text-end $ 5.000.000,00
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-12.col-lg-10.col-xl-9.mx-auto(data-aos="fade-right")
              p.fw-bold.text-center Reconocimiento posterior a 31 de diciembre. Por la contabilización del instrumento de cobertura a su valor razonable, con cambios en los resultados del ejercicio
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 23.
                span Reclasificación de inversión financiera a instrumento derivado de cobertura a largo plazo
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Activos por derivados financieros a largo plazo, instrumentos de cobertura
                      td.text-end $ 300.000,00
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Inversiones financieras a largo plazo en instrumentos de patrimonio
                      td.text-end -
                      td.text-end $ 300.000,00
    separador

    .fondo-slider(style="background: linear-gradient(0deg, rgba(0,0,0,0) 0%, rgba(255,245,234) 30%, rgba(255,245,234) 80%, rgba(0,0,0,0) 100%);")
      #t_2_2.titulo-segundo.color-acento-contenido
        h2 2.2 Aportes de capital
      
      .d-flex.flex-wrap.mb-5
        .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
          p.mb-4 Los aportes iniciales de los socios corresponden al capital y están representados en acciones, libremente negociables en las bolsas de valores. 
          ul.lista-ul.mb-4
            li
              i.fas.fa-angle-right.txt--purple
              | #[b Autorizado:] es el valor máximo de capitalización de una sociedad. 
            li
              i.fas.fa-angle-right.txt--purple
              | #[b Suscrito:] es la parte del capital autorizado, que los accionistas se comprometen a pagar, como si fuera una venta a plazos, sin superar el año, artículo 387 del Código del Comercio. Para el caso de las sociedades simplificadas por acciones S.A.S., el plazo es de dos años acorde a la Ley 1258 de 2008, artículo 387. 
            li
              i.fas.fa-angle-right.txt--purple
              | #[b Pagado:] es la parte del capital suscrito que los accionistas han cancelado y que efectivamente se encuentra en poder de la sociedad.
          p.mb-0.p-4(style="background-color: #E6DCFB") #[b Ejemplo.]
            br
            br
            |En 2017 se constituyó la empresa Aprendiendo S.A., con un capital autorizado de 120.000 acciones con un valor por acción de $ 2.500, los accionistas suscribieron el 50 % de las acciones autorizadas y pagaron el 70 % de la suscripción.
        .mx-auto.col-md-7.col-lg-5.order-1.order-lg-2
          img(src="@/assets/curso/tema2/img-5.svg", alt="", style="max-width: 505px").mx-auto.mb-4.ps-lg-4


      .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
        .col
          h3 Reconocimiento inicial

      p.mb-5 A continuación, se presentan los asientos contables correspondientes al reconocimiento inicial del capital autorizado, suscrito y pagado:

      .col-lg-10.col-xl-6.mx-auto.mb-5
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 24.
          span Primer registro: capital autorizado y por suscribir
        .tabla-a.mb-4(data-aos="fade-up")
          table.table-type-1
            thead
              tr
                th Cuenta
                th Débitos
                th Créditos
            tbody
              tr.bg-white
                td.text-start Capital por suscribir
                td.text-end $ 300.000.000
                td.text-end -
              tr.bg-white
                td.text-start Capital autorizado
                td.text-end -
                td.text-end $ 300.000.000

        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 25.
          span Segundo registro: capital suscrito y pagado parcialmente
        .tabla-a.mb-4(data-aos="fade-up")
          table.table-type-1
            thead
              tr
                th Cuenta
                th Débitos
                th Créditos
            tbody
              tr.bg-white
                td.text-start Efectivo y sus equivalentes
                td.text-end $ 105.000.000
                td.text-end -
              tr.bg-white
                td.text-start Capital suscrito por pagar
                td.text-end $ 45.000.000
                td.text-end -
              tr.bg-white
                td.text-start Capital por suscribir
                td.text-end -
                td.text-end $ 150.000.000


      .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
        .col
          h3 Detalle de las cuentas
      
      p.mb-5 Se presentan a continuación los datos relacionados con el capital autorizado, suscrito y pagado:

      .col-lg-10.col-xl-6.mx-auto.py-5.px-3.px-md-5.mb-5(style="background-color: white; box-shadow: 0px 0px 5px 1px rgba(0, 0, 0, 0.15)")
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5 Capital autorizado
          .span 120.000 acciones
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5 Valor por acción
          .span $2.500,00
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5
          .col-4(style="border-bottom: 1px solid black")
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5 Valor total
          .span $300.000.000
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5
          .col-4(style="border-bottom: 1px solid black")
        .col-12.d-flex.justify-content-between
          .span.pe-5 Capital suscrito
          .span 50 %

      .col-lg-10.col-xl-6.mx-auto.py-5.px-3.px-md-5.mb-5(style="background-color: white; box-shadow: 0px 0px 5px 1px rgba(0, 0, 0, 0.15)")
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5 Total suscrito
          .span $150.000.000
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5 Pagado
          .span 70 %
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5
          .col-4(style="border-bottom: 1px solid black")
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5 Total capital pagado
          .span $105.000.000
        .col-12.d-flex.justify-content-between.mb-3
          .span.pe-5
          .col-4(style="border-bottom: 1px solid black")
        .col-12.d-flex.justify-content-between
          .span.pe-5 Capital por pagar
          .span $45.000.000
      
      .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
        .col
          h3 Presentación

      p.mb-5 A continuación, se presenta el estado de situación financiera inicial de la empresa:

      .d-flex.flex-wrap.mb-5
        .col-lg-6.mx-auto.py-5.px-3.px-md-5.mb-5.order-2.order-lg-1(style="background-color: white; box-shadow: 0px 0px 5px 1px rgba(0, 0, 0, 0.15)" data-aos="fade-right")
          p Aprendiendo S.A.
          p Estados de situación Financiera Inicial
          p A 1/1/17
          p.py-3.fw-bold Activos
          p.mb-4 Activo corriente
          .linea-points.v2
            span.label(style="background-color: white") efectivo y sus equivalentes
            span.value(style="background-color: white") $105.000.000
          .linea-points.v2
            span.label(style="background-color: white") Total, activos
            span.value(style="background-color: white") $105.000.000
          p.mb-0.fw-bold Pasivos
          .linea-points.v2.mb-4
            span.label(style="background-color: white") Total, pasivos
            span.value(style="background-color: white") $0
          p.mb-1 Patrimonio
          p.mb-4 Capital social
          .linea-points.v2.mb-3
            span.label(style="background-color: white") Capital autorizado
            span.value(style="background-color: white") $300.000.000
          .linea-points.v2.mb-3
            span.label(style="background-color: white") Capital por suscribir
            span.value(style="background-color: white") $(150.000.000)
          .linea-points.v2.mb-3
            span.label(style="background-color: white") Capital suscrito por cobrar
            span.value(style="background-color: white") $(45.000.000)
          .linea-points.v2.mb-3
            span.label(style="background-color: white") Total, patrimonio
            span.value(style="background-color: white") $105.000.000
          .linea-points.v2.mb-3
            span.label(style="background-color: white") Total, pasivo y patrimonio
            span.value(style="background-color: white") $105.000.000

        .mx-auto.col-md-6.order-1.order-lg-2
          img(src="@/assets/curso/tema2/img-10.svg", alt="", style="max-width: 610px").mx-auto.mb-4.ps-lg-4

      separador

      #t_2_3.titulo-segundo.color-acento-contenido
        h2 2.3 Ganancias acumuladas
      
      .d-flex.flex-wrap.align-items-center
        .col-lg-5.mb-4.mb-lg-0.mx-auto(data-aos="fade-right")
          img(src="@/assets/curso/tema2/img-11.png" style="max-width: 502px").mx-auto
        .col-lg-7.mb-4.mb-lg-0.ps-lg-4(data-aos="fade-right")
          .row.align-items-center.py-2.mx-0.mb-4(style="background-color: #DDEFFD")
            .col-auto
              figure(data-aos="fade-up")
                img.mb-4.mb-lg-0(src="@/assets/curso/tema2/img-12.svg", alt="" style="max-width: 81px").m-auto
            .col-xl
              p.mb-0 Es el dinero guardado que no es entregado a los accionistas en forma de dividendos, estas ganancias se encuentran en el patrimonio como ganancias acumuladas en el estado de situación financiera.
          p.mb-0 De igual forma, se relaciona en el estado de cambios en el patrimonio; cuyo objetivo, es mostrar los cambios o variaciones presentadas de un periodo a otro. Entre las variaciones que se analizan y que son significativas para dicho estado financiero, se puede observar la política de dividendos que maneja la entidad, donde se encuentra estipulado no distribuir el 100 % de las utilidades del ejercicio, de tal manera, que la parte no decretada para reparto, queda acumulada hasta tanto los socios decidan distribuirla entre los accionistas.

    separador

    #t_2_4.titulo-segundo.color-acento-contenido
      h2 2.4 Reservas
    
    p.mb-5 Están contempladas en los artículos 452, 453 y 454 del Código del Comercio, sección II reparto de utilidades.

    TabsC.color-acento-botones
      .py-3.py-md-4(titulo="Art. 452" style="background-color: #F9F7F4")
        .d-flex.flex-wrap.col-xl-11.mx-auto
          .col-lg-8.mb-4.mb-md-0.pe-lg-4.order-2.order-lg-1
            h4 Reserva legal
            p Las sociedades anónimas constituirán una reserva legal que ascenderá por lo menos al cincuenta por ciento del capital suscrito, formada con el diez por ciento de las utilidades líquidas de cada ejercicio. Cuando esta reserva llegue al cincuenta por ciento mencionado, la sociedad no tendrá obligación de continuar llevando a esta cuenta el diez por ciento de las utilidades líquidas. Pero si disminuye, volverá a apropiarse el mismo diez por ciento de tales utilidades hasta cuando la reserva llegue nuevamente al límite fijado. Conc.: 110 num. 8o, 154, 271 num. 4o, 272 num. 5o., 350, 371, 454, 456, 476. (Legis. 2020).
          .col-12.col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
            img(src='@/assets/curso/tema2/img-13.svg', alt='' style="max-width: 250px").mx-auto


      .py-3.py-md-4(titulo="Art. 453" style="background-color: #F9F7F4")
        .d-flex.flex-wrap.col-xl-11.mx-auto
          .col-lg-8.mb-4.mb-md-0.pe-lg-4.order-2.order-lg-1
            h4 Reservas estatutarias y ocasionales
            p Art. 453. Reservas estatutarias y ocasionales. Las reservas estatutarias serán obligatorias mientras no se supriman mediante una reforma del contrato social, o mientras no alcancen el monto previsto para las mismas. Las reservas ocasionales que ordene la asamblea solo serán obligatorias para el ejercicio en el cual se hagan y la misma asamblea podrá cambiar su destinación o distribuirlas cuando resulten innecesarias. (leyes estatutarias 2020).
          .col-12.col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
            img(src='@/assets/curso/tema2/img-13.svg', alt='' style="max-width: 250px").mx-auto


      .py-3.py-md-4(titulo="Art. 454" style="background-color: #F9F7F4")
        .d-flex.flex-wrap.col-xl-11.mx-auto
          .col-lg-8.mb-4.mb-md-0.pe-lg-4.order-2.order-lg-1
            h4 Incremento en el porcentaje de distribución de utilidades
            p Art. 454. Incremento en el porcentaje de distribución de utilidades. Si la suma de las reservas legal, estatutaria y ocasional excediere del ciento por ciento (100 %) del capital suscrito, el porcentaje obligatorio de utilidades líquidas que deberá repartir la sociedad conforme al artículo 155, se elevará al setenta por ciento. (Código de Comercio Colombiano, 1971).
              br
              br
              |La reserva legal es un ahorro que las empresas por mandato legal en Colombia están obligadas a utilizar con el fin de proteger el capital y preservar las empresas en el futuro evitando disolverse o liquidarse por la disminución de su patrimonio. Las sociedades limitadas, las anónimas, las en comandita por acciones y las extranjeras. Deben hacer uso de la figura reserva legal. En el primer año, no se efectúan reservas; es decir, no aplica el 10 % sobre las utilidades.
          .col-12.col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
            img(src='@/assets/curso/tema2/img-13.svg', alt='' style="max-width: 250px").mx-auto


      .py-3.py-md-4(titulo="Art. 456" style="background-color: #F9F7F4")
        .d-flex.flex-wrap.col-xl-11.mx-auto
          .col-lg-8.mb-4.mb-md-0.pe-lg-4.order-2.order-lg-1
            p Según el Código del Comercio, sección II reparto de utilidades artículo 456, las reservas se utilizan para:
            h4 Reservas estatutarias y ocasionales
            p Art. 456. Manejo de pérdidas. Las pérdidas se enjugarán con las reservas que hayan sido destinadas especialmente para ese propósito y, en su defecto, con la reserva legal. Las reservas cuya finalidad fuere la de absorber determinadas pérdidas no se podrán emplear para cubrir otras distintas, salvo que así lo decida la asamblea. Si la reserva legal fuere insuficiente para enjugar el déficit de capital, se aplicarán a este fin los beneficios sociales de los ejercicios siguientes.
              br
              br
              |La reserva legal para las sociedades de responsabilidad limitada aplicará el 10 % de reservas frente a sus utilidades acorde al libro segundo, responsabilidad limitada del Código del Comercio:
          .col-12.col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
            img(src='@/assets/curso/tema2/img-13.svg', alt='' style="max-width: 250px").mx-auto


      .py-3.py-md-4(titulo="Art. 371" style="background-color: #F9F7F4")
        .d-flex.flex-wrap.col-xl-11.mx-auto
          .col-lg-8.mb-4.mb-md-0.pe-lg-4.order-2.order-lg-1
            h4 Reserva legal, balances y reparto de utilidades
            p Art. 371. Reserva legal, balances y reparto de utilidades. La sociedad formará una reserva legal, con sujeción a las reglas establecidas para la anónima. Estas mismas reglas se observarán en cuanto a los balances de fin de ejercicio y al reparto de utilidades. (Código de Comercio Colombiano, 2020b).
              br
              br
              |En las sociedades extranjeras aplicará el 10 % de reserva legal, como es aplicado en las sociedades anónimas, sin importar el tamaño de la empresa.
          .col-12.col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
            img(src='@/assets/curso/tema2/img-13.svg', alt='' style="max-width: 250px").mx-auto


      .py-3.py-md-4(titulo="Art. 476" style="background-color: #F9F7F4")
        .d-flex.flex-wrap.col-xl-11.mx-auto
          .col-12.col-lg-6.mb-4.mb-lg-0.pe-lg-4
            h4 Reservas y vigilancia
            p Art. 476. Reservas y vigilancia. Las sociedades extranjeras con negocios permanentes en Colombia constituirán las reservas y provisiones que la ley exige a las anónimas nacionales y cumplirán los demás requisitos establecidos para su control y vigilancia.
            p.mb-0 Frente a la utilidad se aplica el porcentaje vigente definido en cada reforma tributaria, del resultado obtenido, se aplica el 10 % de reserva legal y se resta a la utilidad líquida.
          .col-12.col-lg-6
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 26.
              span Determinación de utilidad neta y distribución a los accionistas
            .tabla-a(data-aos="fade-up")
              table.table-type-1
                thead
                  tr
                    th.py-3(colspan="2") Concepto
                    th.py-3 Valor
                tbody
                  tr
                    td.py-3(colspan="2").text-start Utilidad
                    td.py-3.texto-right $ 5.000.000,00
                  tr
                    td.py-3(colspan="2").text-start Menos impuesto de renta 32 %
                    td.py-3.texto-right $ 1.600.000,00
                  tr
                    td.py-3(colspan="2").text-start Utilidad neta
                    td.py-3.texto-right $  3.400.000 
                  tr
                    td.py-3(colspan="2").text-start Reserva legal 10 %
                    td.py-3.texto-right $ 340.000,00
                  tr
                    td.py-3(colspan="2").text-start Utilidad a distribuir a los o accionistas
                    td.py-3.texto-right $ 3.060.000,00
    separador

    #t_2_5.titulo-segundo.color-acento-contenido
      h2 2.5 Otro resultado integral (ORI)

    .d-flex.flex-wrap.mb-5
      .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
        p.mb-4.p-4(style="background-color: #FEEAD4") Una entidad presentará su resultado integral total para un periodo: en un único estado del resultado integral, en cuyo caso el estado del resultado integral presentará todas las partidas de ingreso y gasto reconocidas en el periodo además de las partidas correspondientes a utilidades no realizadas, o en dos estados -un estado de resultados y un estado del resultado integral-, en cuyo caso el estado de resultados presentará todas las partidas de ingreso y gasto reconocidas en el periodo excepto las que estén reconocidas en el resultado integral total fuera del resultado.
        p.mb-4 Se reconocen como otro resultado integral y forman parte del resultado integral total, cuando se producen:
          br
          br
          | #[b Clases:]
        ul.lista-ul.mb-4
          li
            i.fas.fa-angle-right.txt--purple
            | Diferencias en cambio que surjan de la conversión de moneda extranjera.
          li
            i.fas.fa-angle-right.txt--purple
            | Diferencias en cálculos actuariales.
          li
            i.fas.fa-angle-right.txt--purple
            | Cambios en los importes recuperables de activos revalorizados con cambios en el patrimonio.
      .mx-auto.col-lg-5.order-1.order-lg-2
        img(src="@/assets/curso/tema2/img-14.png", alt="", style="max-width: 505px").mx-auto.mb-4.ps-lg-4

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.p-5(style="background-color: #412976")
        .d-flex.flex-wrap.flex-md-nowrap.align-items-end.mb-4
          img.mb-4(src="@/assets/curso/tema2/img-15.svg", alt="", style="max-width: 76px")
          h4.mb-0.ms-3.ms-md-3.px-2.py-1(style="background-color: #FD9826") Ejemplo: presentación ORI

        .linea-points
          span.label Ingresos ordinarios
          span.value 500
        .linea-points
          span.label Costo ventas
          span.value 200
        .linea-points
          span.label Utilidad bruta
          span.value 300
        .linea-points
          span.label Gastos de operación
          span.value 100
        .linea-points
          span.label Utilidad antes de impuestos
          span.value 200
        .linea-points
          span.label Impuesto renta
          span.value 70
        .linea-points
          span.label Utilidad neta
          span.value 130
      .col-md.tarjeta.p-5(style="background-color: #E8E8E8")
        .d-flex.flex-wrap.flex-md-nowrap.align-items-end.mb-4
          img.mb-4(src="@/assets/curso/tema2/img-15.svg", alt="", style="max-width: 76px")
          h4.mb-0.ms-3.ms-md-3.px-2.py-1(style="background-color: #FD9826") Otro resultado integral
        
        .linea-points.v2
          span.label Variación valor razonable
          span.value 100
        .linea-points.v2
          span.label Conversión moneda extranjera
          span.value 150
        .linea-points.v2
          span.label Cálculo actuarial
          span.value 50
        .linea-points.v2
          span.label Valor razonable instrumentos financieros
          span.value 45
        .linea-points.v2
          span.label Total, ORI
          span.value 345
        .linea-points.v2
          span.label Resultado integral total
          span.value 475

    .row.caja-text-img-tema1.align-items-center.mx-0.mb-5.py-3(style="background-color: #8454EE")
      .col-xl-auto
        figure(data-aos="fade-right").d-none.d-xl-block
          img(src="@/assets/curso/tema1/img-1.png", alt="" style="max-width: 100px").m-auto
      .col-xl
        p.mb-0.text-white.fw-bold A continuación, se relacionan algunos conceptos que se deben tener en cuenta en el reconocimiento y medición de instrumentos financieros:

    .d-flex.flex-wrap
      .col-lg-6.mx-auto.py-5.mb-5.order-2.order-lg-1(data-aos="fade-right")
        .col-xl.mb-4.px-0
          a.anexo.ajuste__movil_anexo.mb-4.mb-lg-0(href="https://www.aplicaciones-mcit.gov.co/adjuntos/niif/12_ES_BV2012_IFRS07_PART%20A.pdf" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg")
            .anexo__texto
              p #[b Enlace web.] Ministerio de Comercio, Industria y Turismo, 2012.
        .col-xl.mb-4.px-0
          a.anexo.ajuste__movil_anexo.mb-4.mb-lg-0(href="https://www.ctcp.gov.co/proyectos/contabilidad-e-informacion-financiera/documentos-discusion-publica/enmienda-a-la-niif-9-instrumentos/doc-ctcp-xl8w9-141" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg")
            .anexo__texto
              p #[b Enlace web.] Consejo Técnico de la Contaduría Pública, 2014.
        .col-xl.mb-4.px-0
          a.anexo.ajuste__movil_anexo.mb-4.mb-lg-0(href="https://www.ctcp.gov.co/proyectos/contabilidad-e-informacion-financiera/documentos-organismos-internacionales/compilacion-marcos-tecnicos-de-informacion-financi/1534365029-7113" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg")
            .anexo__texto
              p #[b Enlace web.] Consejo Técnico de la Contaduría Pública, Norma Internacional de Contabilidad NIC 32.
        .col-xl.mb-4.px-0
          a.anexo.ajuste__movil_anexo.mb-4.mb-lg-0(href="https://www.ctcp.gov.co/publicaciones-ctcp/orientaciones-tecnicas/1472852072-9672" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg")
            .anexo__texto
              p #[b Enlace web.] Consejo Técnico de la Contaduría Pública, 2015, P.2.
        .col-xl.mb-4.px-0
          a.anexo.ajuste__movil_anexo.mb-4.mb-lg-0(href="http://www.ctcp.gov.co/publicaciones-ctcp/orientaciones-tecnicas/1472851475-1578" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg")
            .anexo__texto
              p #[b Enlace web.] Consejo Técnico de la Contaduría Pública, 2014, P.8.
      .mx-auto.col-md-8.col-lg-6.order-1.order-lg-2
        img(src="@/assets/curso/tema2/img-16.svg", alt="", style="max-width: 610px").mx-auto.mb-4.ps-lg-4


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

<style lang="sass" scoped>
.linea-points
  display: flex
  align-items: center
  position: relative
  justify-content: space-between
  &::before
    content: ""
    position: absolute
    top: 0
    left: 0
    width: 99%
    height: 70%
    color: white
    overflow: hidden
    white-space: nowrap
    pointer-events: none
    display: flex
    align-items: center
    border-bottom: 2px dotted white
  .label, .value
    color: white
    position: relative
    z-index: 1
    padding: 5px
    background-color: #412976
  .label
    margin-right: 1rem
  &.v2
    &::before
      border-bottom: 3px dotted #12263F
    .label, .value
      color: #12263F
      background-color: #E8E8E8
</style>
