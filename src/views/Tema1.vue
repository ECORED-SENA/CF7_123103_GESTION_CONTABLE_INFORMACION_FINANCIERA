<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Instrumentos financieros: activos, pasivos e instrumentos de patrimonio
    .bg-gradient-1
      .row.caja-text-img-tema1.align-items-center.mx-0.mb-0(style="background-color: #8454EE")
        .col-xl-auto
          figure(data-aos="fade-up").d-none.d-xl-block
            img(src="@/assets/curso/tema1/img-1.png", alt="" style="max-width: 100px").m-auto
        .col-xl
          p.mb-0.text-white.fw-bold A continuación, se relacionan algunos conceptos que se deben tener en cuenta en el reconocimiento y medición de instrumentos financieros:

      .row.ajuste-espacios-movil.pt-5
        .col-xl
          TabsA.color-acento-botones.mb-4
            .tarjeta.color-acento-botones--borde.p-4(titulo="Activo financiero")
              h4 Activo financiero
              .d-flex.flex-wrap.align-items-center.gap-3
                p.order-2.order-md-1.col-12.col-md Los activos financieros se clasifican de acuerdo al modelo de negocio del suscriptor en tres categorías: a su costo amortizado, a valor razonable con cambios en el patrimonio (otro resultado integral) o a valor razonable con cambios en pérdidas y ganancias, dependiendo de las características de los flujos de efectivo descritos en el documento que protocoliza el instrumento financiero, por ejemplo, el cobro de los rendimientos generados por el activo o tener la intención de vender el activo. (Norma internacional de información financiera, 2016, p. 9).
                img.mx-auto.order-1.order-md-2(src="@/assets/curso/tema1/img-2.svg", alt="", style="max-width: 155px").m-auto
            .tarjeta.color-acento-botones--borde.p-4(titulo="Pasivo financiero")
              h4 Pasivo financiero
              .d-flex.flex-wrap.align-items-center.gap-3
                p.order-2.order-md-1.col-12.col-md Generalmente, los pasivos financieros se miden a costo amortizado, excepto aquellos pasivos financieros que se mantienen para negociar, como por ejemplo los derivados, que se valoran a valor razonable con cambios en resultados.
                img.mx-auto.order-1.order-md-2(src="@/assets/curso/tema1/img-3.svg", alt="", style="max-width: 155px").m-auto
            .tarjeta.color-acento-botones--borde.p-4(titulo="Patrimonio")
              h4 Patrimonio
              .d-flex.flex-wrap.align-items-center.gap-3
                p.order-2.order-md-1.col-12.col-md Un instrumento de patrimonio es cualquier contrato que ponga de manifiesto una participación residual en los activos de una entidad, después de deducir todos sus pasivos. (Norma Internacional de Contabilidad, s.f. p. 2).
                img.mx-auto.order-1.order-md-2(src="@/assets/curso/tema1/img-4.svg", alt="", style="max-width: 155px").m-auto

    separador

    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Política contable
    
    p Son los principios, bases, acuerdos, reglas y procedimientos específicos adoptados por la entidad en la elaboración y presentación de los estados financieros.

    p.mb-5 #[b Una política contable debe contener:]

    .d-flex.flex-wrap.mb-5
      .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
        ul.lista-ul.mb-4
          li
            i.fas.fa-angle-right.txt--purple
            | Nombre de la política contable.
          li
            i.fas.fa-angle-right.txt--purple
            | Debe establecer los criterios de reconocimiento del hecho económico, medición inicial, medición posterior y las revelaciones requeridas.
          li
            i.fas.fa-angle-right.txt--purple
            | Objetivo de la política contable.
        .row.align-items-center.py-2.mx-0.mb-4(style="background-color: #FEEAD4")
          .col-auto
            figure(data-aos="fade-up")
              img.mb-4.mb-lg-0(src="@/assets/curso/tema1/img-6.svg", alt="" style="max-width: 81px").m-auto
          .col-xl
            p.mb-0 La Norma Internacional de Información Financiera NIIF 9 define cómo se deben reconocer y medir los instrumentos financieros.
        
        p.mb-0 La normativa que se debe tener en cuenta para la aplicación de instrumentos financieros es la siguiente:
      .mx-auto.col-md-7.col-lg-5.order-1.order-lg-2
        img(src="@/assets/curso/tema1/img-5.svg", alt="", style="max-width: 505px").mx-auto.mb-4.ps-lg-4

    .titulo-sexto.color-acento-contenido.mb-2
      h5 Figura 1.
      span Normativa para la aplicación de instrumentos financieros
    .px-4.py-5.mb-5(style="background-color: #F3F0EA")
      figure
        img(src="@/assets/curso/tema1/img-7.svg" style="max-width: 540px" alt="Diagrama sobre normativa para la aplicación de instrumentos financieros que incluye la NIC 32 relacionada con alcance y definiciones, las NIIF 9 y NIC 39 sobre medición y reconocimiento, y la NIIF 7 enfocada en revelación.").m-auto

    .d-flex.flex-wrap
      .col-md-7.col-lg-5.mb-4.mb-lg-0.mx-auto(data-aos="fade-right")
        img(src="@/assets/curso/tema1/img-8.png" style="max-width: 502px").mx-auto
      .col-lg-7.mb-4.mb-lg-0.ps-lg-4(data-aos="fade-right")
        p.mb-4 Una entidad optará entre aplicar dependiendo del grupo al que pertenece:
        ol.lista-ol
          li.d-flex
            .lista-ol--cuadro__vineta.v--green
              span a
            | Lo previsto en la sección 11 y sección 12 si pertenece al grupo número dos pymes.
          li.d-flex
            .lista-ol--cuadro__vineta.v--green
              span b
            | Las disposiciones sobre reconocimiento y medición de la NIIF 9 Instrumentos financieros si pertenece al grupo número uno.
        p.mb-0.p-4.px-lg-5(style="background-color: #DDEFFD") Cuando se aplique un cambio de una política contable, se hará de forma retroactiva, como si la nueva política contable se hubiese aplicado siempre. Cuando sea impracticable determinar los efectos en cada periodo específico de un cambio en una política contable sobre la información comparativa para uno o más periodos anteriores para los que se presente información, la entidad aplicará la nueva política contable a los importes en libros de los activos y pasivos al principio del primer periodo para el que sea practicable la aplicación retroactiva, el cual podría ser el periodo actual.

    separador

    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2 Instrumentos financieros
    p.mb-5 Para la ejecución de los instrumentos financieros es necesario conocer algunos elementos que son esenciales para el desarrollo e implementación de los mismos, estos elementos serán abordados a continuación.

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
      .col
        h3 Activo financiero
    
    p.mb-5 Un activo financiero es cualquier activo que posea la forma de efectivo, instrumento de patrimonio neto de otra entidad o que represente un derecho contractual o un contrato que pueda ser liquidado utilizando instrumentos de patrimonio propio de la entidad. Los activos financieros deben ser medidos al costo amortizado, pero si son mantenidos para negociar, se miden a valor razonable con cambios en el resultado del ejercicio.

    .col-12.col-lg-10.col-xl-8.mx-auto.mb-5(data-aos="fade-right")
      .titulo-sexto.color-acento-contenido.mb-3
        h5 Tabla 1. 
        span Factura
      .tabla-a.mb-4(data-aos="fade-up")
        table.table-type-1
          thead
            tr
              th Concepto
              th Valor
          tbody
            tr
              td.text-start Precio factura
              td.text-end $502.500
            tr
              td.text-start Descuento
              td.text-end $11.400
            tr
              td.text-start Base gravable
              td.text-end $491.100
            tr
              td.text-start IVA 19 %
              td.text-end $95.475
            tr
              td.text-start Total, facturado
              td.text-end $586.575

    .d-flex.flex-wrap.mb-5
      .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
        p.p-4.px-lg-5.mb-4(style="background-color: #DDEFFD")
          | #[b Ejemplo.]
          br
          br
          | El 17/11/año 1, la sociedad contable SAS vendió a crédito 5.000 unidades del producto ZV a $ 100,50 por unidad, se ha concedido sobre la factura un descuento de $ 11.400. El pago se realizará dentro de 2 años y el descuento es del 5 %.
        p El crédito constituye para el vendedor un activo financiero, pues es un derecho contractual.
        p Como es una transacción a largo plazo, se debe reconocer el valor del dinero en el tiempo a la tasa del 5 % efectiva anual, lo que implica el cálculo del valor presente del valor de la venta neta (491.100) para reconocer al final del año 1 y 2 el ajuste por concepto de los gastos financieros así:  
      .mx-auto.col-lg-5.order-1.order-lg-2
        img(src="@/assets/curso/tema1/img-9.png", alt="", style="max-width: 472px").mx-auto.mb-4.ps-lg-4

    .row.fondo-slider.mb-5.ajuste-espacios-movil(:style="{'background-image': `url(${require('@/assets/curso/tema1/img-bg-table.jpg')})`}")
      .ajuste-slider
        SlyderA(tipo="b")
          .col-lg-8.mb-4.col-xs-12.mx-auto
            p.mb-4.fw-bold Al fin del año 1 reconocimiento posterior del componente financiero
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 2. 
              span Cálculo del valor facturado con descuento e IVA
            .tabla-a.mb-4(data-aos="fade-up")
              table.table-type-1
                thead
                  tr
                    th Clasificación
                    th Cuentas
                    th Debe
                    th Haber
                tbody
                  tr
                    td.text-start Activo largo plazo
                    td.text-start Clientes a largo plazo
                    td.text-end $22.272,11
                    td.text-end -
                  tr
                    td.text-start Ingreso
                    td.text-start Ingreso financiero
                    td.text-end -
                    td.text-end $22.272,11
          .col-lg-8.mb-4.col-xs-12.mx-auto
            p.mb-4.fw-bold Al final del año 2 reconocimiento posterior del componente financiero
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 3. 
              span Reconocimiento de ingreso financiero por cuentas a largo plazo
            .tabla-a.mb-4(data-aos="fade-up")
              table.table-type-1
                thead
                  tr
                    th Clasificación
                    th Cuentas
                    th Debe
                    th Haber
                tbody
                  tr
                    td.text-start Activo largo plazo
                    td.text-start Clientes a largo plazo
                    td.text-end $23.385,71
                    td.text-end -
                  tr
                    td.text-start Ingreso
                    td.text-start Ingreso financiero
                    td.text-end -
                    td.text-end $23.385,71
          .col-lg-8.mb-4.col-xs-12.mx-auto
            p.mb-4.fw-bold Por reclasificar el crédito del largo al corto plazo
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 4. 
              span Reclasificación de cuentas por cobrar de largo a corto plazo
            .tabla-a.mb-4(data-aos="fade-up")
              table.table-type-1
                thead
                  tr
                    th Clasificación
                    th Cuentas
                    th Debe
                    th Haber
                tbody
                  tr
                    td.text-start Activo corto plazo
                    td.text-start Clientes
                    td.text-end $563.189,29
                    td.text-end -
                  tr
                    td.text-start Activo largo plazo
                    td.text-start Clientes a largo plazo
                    td.text-end -
                    td.text-end $563.189,29
          .col-lg-8.mb-4.col-xs-12.mx-auto
            p.mb-4.fw-bold Reconocimiento por cobro de crédito
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 5. 
              span Registro del recaudo de cartera por venta a crédito
            .tabla-a.mb-4(data-aos="fade-up")
              table.table-type-1
                thead
                  tr
                    th Clasificación
                    th Cuentas
                    th Debe
                    th Haber
                tbody
                  tr
                    td.text-start Activo corto plazo
                    td.text-start Bancos
                    td.text-end $586.575
                    td.text-end -
                  tr
                    td.text-start Activo corto plazo
                    td.text-start Clientes
                    td.text-end -
                    td.text-end $586.575
    .row.mb-4.ajuste-espacios-movil.mb-5
      .col.ajuste-h4
        h4 Conceptos
    
    .row.mb-5.m-0.ajuste-espacios-movil
      .col-lg-6.espacio__cajas_movil
        .ajuste-caja-text-bloque4.h-100(data-aos="flip-left" style="background-color: #BCE0FC")
          .col
            figure.mb-3
              img(src='@/assets/curso/tema1/img-10.svg', alt='T' style="max-width: 95px").m-auto
            .row.mb-4.ajuste-espacios-movil.text-center
              .col.ajuste-h4
                h4.mb-0(style="background-color: #EDF7FE")  Costo amortizado
            p.mb-0 Es el importe al que inicialmente fue valorado un pasivo financiero, menos los pagos de principal que se hubieran producido, menos los intereses correspondientes a los períodos calculados con la técnica del tipo de interés efectivo. (Supercontable Sage, s.f p. 9).
      .col-lg-6.espacio__cajas_movil
        .ajuste-caja-text-bloque4.h-100(data-aos="flip-left" style="background-color: #BCE0FC")
          .col
            figure.mb-3
              img(src='@/assets/curso/tema1/img-11.svg', alt='' style="max-width: 95px").m-auto
            .row.mb-4.ajuste-espacios-movil.text-center
              .col.ajuste-h4
                h4.mb-0(style="background-color: #EDF7FE") Método de la tasa de interés efectiva
            p.mb-0 Es un método para calcular el costo amortizado de un pasivo, calculando la tasa de descuento para igualar los flujos de efectivo, en el periodo cero o periodo de medición; es decir, es la tasa que se le aplicará al instrumento financiero para calcular los intereses. Tomado de: Actualícese (2017, 17 de mayo).

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
      .col
        h3 Pasivos financiero
    
    .d-flex.flex-wrap.mb-5
      .col-md-7.col-lg-5.mb-4.mb-lg-0.mx-auto(data-aos="fade-right")
        img(src="@/assets/curso/tema1/img-12.png" style="max-width: 502px").mx-auto
      .col-lg-7.mb-4.mb-lg-0.ps-lg-4(data-aos="fade-right")
        p.mb-4.p-4(style="background-color: #E6DCFB") Es cualquier pasivo que represente una obligación contractual de entregar dinero u otro activo financiero a otra entidad o de intercambiar activos financieros o pasivos financieros con otra entidad o un contrato que sea liquidado utilizando los instrumentos de patrimonio propio de la entidad, debe ser medido al costo amortizado utilizando la técnica del interés efectivo, sin embargo, si es para negociar, incluidos los instrumentos derivados, se mide a valor razonable con cambios en el estado de resultados. (Instrumentos financieros NIC 32 s.f p. 9).
        p #[b Valor razonable:] es la intermediación efectiva que se hace a través de la oferta y demanda de forma libre, dicho de otra forma, es la interacción de un comprador y un vendedor, que se obligan y comprometen a transar una cantidad de bien determinando un precio y unas condiciones específicas en un mercado libre.
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
      .col
        h3 Reconocimiento y medición

    .d-flex.flex-wrap.mb-5.fondo-slider(style="background: rgb(0,0,0); background: linear-gradient(0deg, transparent 0%, rgba(243,240,234,1) 25%, rgba(243,240,234,1) 75%, transparent 100%);")
      .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
        p.mb-4 #[b Medición inicial:] se genera en el momento en que se realiza el hecho económico, incluidos los costos indirectos de constitución del título.
        p.mb-4 #[b Medición posterior:] se genera en los momentos futuros al reconocimiento inicial y comprende los ajustes propios del instrumento, dependiendo del modelo de negocio que implicó su reconocimiento como para negociar o para la venta, por ejemplo, de tal manera que cuando se presente la información financiera, los instrumentos estén valorados correctamente.
        p.mb-4  Según la normatividad, los instrumentos financieros que se pueden medir a costo amortizado son todos aquellos en los que se desea mantener el activo para cobrar sus flujos de efectivo contractuales, como, por ejemplo:
        ul.lista-ul.mb-4
          li
            i.fas.fa-angle-right.txt--purple
            | TES.
          li
            i.fas.fa-angle-right.txt--purple
            | Bonos.
          li
            i.fas.fa-angle-right.txt--purple
            | Valor razonable: todos aquellos que se adquieren con la intención de ser negociados.
      .mx-auto.col-md-7.col-lg-5.order-1.order-lg-2
        img(src="@/assets/curso/tema1/img-13.svg", alt="", style="max-width: 505px").mx-auto.mb-4.ps-lg-4   


    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
      .col
        h3 Revelación

    .mb-5
      .row.caja-text-img-tema1.align-items-center.mx-0.mb-0(style="background-color: #8454EE")
        .col-xl-auto
          figure(data-aos="fade-up").d-none.d-xl-block
            img(src="@/assets/curso/tema1/img-1.png", alt="" style="max-width: 100px").m-auto
        .col-xl
          p.mb-0.text-white.fw-bold Se debe revelar en las notas a estados financieros la naturaleza de los pasivos financieros, garantías, vencimientos, saldos pendientes de pago y cambios significativos. (NIIF 7)

    separador

    #t_1_3.titulo-segundo.color-acento-contenido
      h2 1.3 Obligaciones con terceros
    
    p.mb-5 Todos los desembolsos requeridos para obtener un crédito con una entidad financiera como estudios de créditos, seguros, entre otros, se deben reconocer en el préstamo. A continuación, encuentra ejemplos que permiten acercarse a un ejercicio real y cotidiano.

    .d-flex.flex-wrap.align-items-center.mb-5
      .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
        p.p-4.px-lg-5.mb-4.mb-lg-0(style="background-color: #FEEAD4")
          | #[b Ejemplo.]
          br
          br
          | La empresa Contable SAS, adquiere un préstamo para desarrollar un proyecto de expansión, por $200.000.000 con una tasa de interés sobre el préstamo pactado en un 2,5 % el interés pactado, 2,5 % es el costo financiero que debe asumir por el préstamo recibido.
      .mx-auto.col-lg-5.order-1.order-lg-2
        img(src="@/assets/curso/tema1/img-14.svg", alt="", style="max-width: 505px").mx-auto.mb-4.mb-lg-0.ps-lg-4 
    p.p-4.px-lg-5.mb-4(style="background-color: #DDEFFD")
      | #[b Ejemplo.]
      br
      br
      | Una empresa, pacta con una entidad financiera una obligación de $120.000, se pacta que, al finalizar 6 años, la empresa entrega a la entidad financiera $138.000 al finalizar los seis años.

    p.mb-5 Determinó el interés efectivo incluido en la negociación utilizando la TIR.

    .titulo-sexto.color-acento-contenido.mb-3
      h5 Tabla 6.
      span Flujo de caja y tasa de retorno

    .col-12.col-lg-10.col-xl-8.mx-auto
      .tabla-a.mb-4(data-aos="fade-up")
        table.table-type-1
          thead
            tr
              th Periodo
              th Montos
          tbody
            tr
              td 0
              td.text-end -$120.000.00
            tr
              td 1
              td.text-end -
            tr
              td 2
              td.text-end -
            tr
              td 3
              td.text-end -
            tr
              td 4
              td.text-end -
            tr
              td 5
              td.text-end $138.000.00
            tr
              td 6
              td.text-end 2,4 %

    p.mb-5 Tabla de amortización: para determinar los costos financieros a ajustar en cada periodo.

    .titulo-sexto.color-acento-contenido.mb-3
      h5 Tabla 7.
      span Tabla de amortización

    .tabla-a.mb-4(data-aos="fade-up")
      table.table-type-1
        thead
          tr
            th Peridos
            th Monto inicial
            th Intereses
            th Monto final
        tbody
          tr
            td 1
            td.text-end $120.000,00
            td.text-end $2.828,05
            td.text-end $122.828,05
          tr
            td 2
            td.text-end $122.28,05
            td.text-end $2894,70
            td.text-end $125.722,75
          tr
            td 3
            td.text-end $125.722,75
            td.text-end $2.962,92
            td.text-end $128.685,66
          tr
            td 4
            td.text-end $128.685,66
            td.text-end $3.032,74
            td.text-end $131.718,41
          tr
            td 5
            td.text-end $131.718,41
            td.text-end $3.104,22
            td.text-end $134.822,63
          tr
            td 6
            td.text-end $134.822,63
            td.text-end $3.177,37
            td.text-end $138.000,00
    separador

    #t_1_4.titulo-segundo.color-acento-contenido
      h2 1.4 Pasivos contingentes

    p.mb-5 Es una obligación posible porque depende de que en el futuro ocurra algo que está fuera del alcance de la empresa para que sea reconocido el compromiso, por lo que los pasivos contingentes no se reconocen, pero sí se revelan.

    .d-flex.flex-wrap.mb-5
      .col-md-7.col-lg-5.mb-4.mb-lg-0.mx-auto(data-aos="fade-right")
        img(src="@/assets/curso/tema1/img-15.svg" style="max-width: 502px").mx-auto
      .col-lg-7.mb-4.mb-lg-0.ps-lg-4(data-aos="fade-right")
        .row.mb-4.ajuste-espacios-movil
          .col.ajuste-h4
            h4.mb-0 Provisiones:
        p Son obligaciones en las cuales no hay certeza en cuanto al monto ni en cuanto a la fecha para su cancelación.
        p.p-4.mb-4(style="background-color: #E6DCFB")
          | #[b Ejemplo.]
          br
          br
          | Una organización espera el resultado de una demanda interpuesta por competencia desleal, los abogados estiman que la empresa tiene una probabilidad alta de perder, el veredicto lo darán los jueces dentro de dos años y se estima el valor de la indemnización en $3.000.000 de pesos.
        p El hecho económico implica reconocer la provisión por valor de tres millones de pesos, pero como se estima para dentro de dos años su reconocimiento, el día de hoy se debe medir a su valor presente utilizando una tasa de descuento de mercado.
    separador

    #t_1_5.titulo-segundo.color-acento-contenido
      h2 1.5 Diferencia entre pasivo financiero e instrumento de patrimonio
    

    .d-flex.flex-wrap.mb-5
      .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
        p.p-4.mb-4(style="background-color: #DDEFFD") El emisor de un instrumento financiero lo clasificará en el momento de su reconocimiento como un pasivo financiero, un activo financiero o un instrumento de patrimonio de conformidad con el acuerdo contractual que protocoliza el instrumento. Una forma de distinguir un pasivo financiero de un instrumento de patrimonio es que exista una obligación contractual que recae sobre cualquiera de las partes de entregar activos o intercambiar pasivos y activos de manera desfavorable para el emisor.
        p Por ejemplo, si se trata de una acción preferencial, esta será reconocida como un pasivo financiero si el emisor está obligado a reembolsar por una cantidad acordada.

        p En el caso de un instrumento con opción de venta, es decir, que el tenedor debe devolverlo al emisor a cambio de efectivo u otro activo se reconoce como un pasivo financiero.
        
      .mx-auto.col-md-7.col-lg-5.order-1.order-lg-2
        img(src="@/assets/curso/tema1/img-16.png", alt="", style="max-width: 505px").mx-auto.mb-4.ps-lg-4   

    separador

    #t_1_6.titulo-segundo.color-acento-contenido
      h2 1.6 Instrumentos financieros pasivos y activos

    p.mb-5 Para el caso de los instrumentos financieros pasivos y activos, aplica la Norma Internacional de Información Financiera (NIIF) 9.

    .fondo-slider.pt-5.mb-5(style="background-color: #F3F0EA")
      .d-flex.flex-wrap.col-xl-10.mx-auto
        .col-lg-6.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
          p.fw-bold Clases:
          ul.lista-ul.mb-4
            li
              i.fas.fa-angle-right.txt--purple
              | Bonos, certificados de depósito a término (CDT).
            li
              i.fas.fa-angle-right.txt--purple
              | Aceptaciones bancarias.
            li
              i.fas.fa-angle-right.txt--purple
              | Pagarés.
            li
              i.fas.fa-angle-right.txt--purple
              | Préstamos.
            li
              i.fas.fa-angle-right.txt--purple
              | Cuentas por cobrar.
          p.fw-bold Instrumentos financieros de cobertura, derivados:
          ul.lista-ul.mb-4
            li
              i.fas.fa-angle-right.txt--purple
              | Opciones.
            li
              i.fas.fa-angle-right.txt--purple
              | #[em Forwards].
            li
              i.fas.fa-angle-right.txt--purple
              | Futuros.
        .mx-auto.col-md-6.col-lg-6.order-1.order-lg-2
          img(src="@/assets/curso/tema1/img-17.svg", alt="", style="max-width: 505px").mx-auto.mb-4.ps-lg-4  

    p.mb-5 Los instrumentos de cobertura son derivados, es decir, activos cuya evolución depende de la que sigan otros (conocidos como subyacentes). Su popularidad se apoya, entre otros factores, en el hecho de que los futuros y muchas opciones se negocien en mercados organizados, lo que permite que estos productos estén al alcance de pequeños inversores.

    .d-flex.flex-wrap.mb-5
      .col-lg-5.mb-4.mb-lg-0.mx-auto(data-aos="fade-right")
        img(src="@/assets/curso/tema1/img-18.svg" style="max-width: 502px").mx-auto
      .d-flex.col-lg-7.mb-4.mb-lg-0.ps-lg-4(data-aos="fade-right")
        p.p-4.mb-4.mb-lg-0(style="background-color: #FEEAD4")
          | #[b Ejemplo:]
          br
          br
          | La sociedad contable SAS realiza el 1/1/año 1 una suscripción de bonos no cotizados cuyas condiciones son las siguientes:

    .titulo-sexto.color-acento-contenido.mb-3
      h5 Tabla 8.
      span Características de la inversión en bonos
    .tabla-a.mb-4(data-aos="fade-up")
      table.table-type-1
        thead
          tr
            th Concepto
            th Valor
            th Unidad
        tbody
          tr
            td.text-start Suscripción
            td 52
            td Bonos
          tr
            td.text-start Valor emisión
            td 7.000
            td Pesos por bono
          tr
            td.text-start Valor reembolso
            td 8.000
            td Pesos por bono
          tr
            td.text-start Fecha reembolso
            td 31/12/año 2
            td -
          tr
            td.text-start Gastos de emisión
            td 1.000
            td Pesos
          tr
            td.text-start Interés anual
            td 3 %
            td EA
    p Se requiere:

    p.mb-5 Contabilizar las operaciones derivadas.

    .row.fondo-slider.mb-5.ajuste-espacios-movil(:style="{'background-image': `url(${require('@/assets/curso/tema1/img-bg-table.jpg')})`, backgroundSize: 'cover'}")
      .ajuste-slider
        SlyderA(tipo="b")
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-lg-7.mb-4.mb-lg-0.ps-lg-4.order-2.order-lg-1(data-aos="fade-right")
              p.fw-bold Cálculo del interés efectivo
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 9.
                span Flujo de caja proyectado por inversión inicial y recuperación en el año 1
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th Periodo
                      th Montos
                  tbody
                    tr
                      td 0
                      td -$363.000
                    tr
                      td AÑO 1
                      td $10.920
            .col-lg-5.mb-4.mb-lg-0.mx-auto.order-1.order-lg-2(data-aos="fade-right")
              img(src="@/assets/curso/tema1/img-19.svg" style="max-width: 298px").mx-auto
          .d-flex.flex-wrap.col-xl-11.mx-auto
            p.col-12.fw-bold Tabla costo amortizado
            .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 10.
                span Tabla costo amortizado
            .tabla-a.mb-4(data-aos="fade-up")
              table.table-type-1(style="min-width: 750px")
                thead
                  tr
                    th Años
                    th Saldo inicial
                    th Interés efectivo
                    th Interés explícito
                    th Interés implícito
                    th Saldo
                tbody
                  tr
                    td Año 1
                    td.text-end $365.000,00
                    td.text-end $36.361,89
                    td.text-end $10.920,00
                    td.text-end $25.441,89
                    td.text-end $390.442
                  tr
                    td Año 2
                    td.text-end $390.441,89
                    td.text-end $38.896,45
                    td.text-end $10.920,00
                    td.text-end $27.976,45
                    td.text-end $418.418
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-lg-8.mb-4.mb-lg-0.ps-lg-4.order-2.order-lg-1(data-aos="fade-right")
              p.fw-bold Año 1. Suscripción
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 11.
                span Año 1. Suscripción
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Valores representativos de deuda a largo plazo
                      td.text-end $365.000,00
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Bancos
                      td.text-end -
                      td.text-end $365.000,00
            .col-lg-4.mb-4.mb-lg-0.mx-auto.order-1.order-lg-2(data-aos="fade-right")
              img(src="@/assets/curso/tema1/img-20.svg" style="max-width: 298px").mx-auto
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-lg-8.mb-4.mb-lg-0.ps-lg-4.order-2.order-lg-1(data-aos="fade-right")
              p.fw-bold Año 1. Cobro del interés explícito
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 12.
                span  Año 1. Cobro del interés explícito
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Bancos
                      td.text-end $10.920,00
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Ingresos de valores representativos de deuda
                      td.text-end -
                      td.text-end $10.920,00
            .col-lg-4.mb-4.mb-lg-0.mx-auto.order-1.order-lg-2(data-aos="fade-right")
              img(src="@/assets/curso/tema1/img-21.svg" style="max-width: 298px").mx-auto
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-lg-8.mb-4.mb-lg-0.ps-lg-4.order-2.order-lg-1(data-aos="fade-right")
              p.fw-bold Año 1. Devengo del interés implícito
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 13.
                span Registro contable por emisión de valores a corto plazo
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Valores representativos de deudas a corto plazo
                      td.text-end $365.000,00
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Bancos
                      td.text-end -
                      td.text-end 365.000,00
            .col-lg-4.mb-4.mb-lg-0.mx-auto.order-1.order-lg-2(data-aos="fade-right")
              img(src="@/assets/curso/tema1/img-22.svg" style="max-width: 298px").mx-auto
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-lg-8.mb-4.mb-lg-0.ps-lg-4.order-2.order-lg-1(data-aos="fade-right")
              p.fw-bold Año 1. Reclasificación de los títulos a corto plazo
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 14.
                span Registro contable por ingresos provenientes de valores representativos de deuda
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Bancos
                      td.text-end $10.920,00
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Ingresos de valores representativos de deuda
                      td.text-end -
                      td.text-end $10.920,00
            .col-lg-4.mb-4.mb-lg-0.mx-auto.order-1.order-lg-2(data-aos="fade-right")
              img(src="@/assets/curso/tema1/img-23.svg" style="max-width: 298px").mx-auto
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-lg-8.mb-4.mb-lg-0.ps-lg-4.order-2.order-lg-1(data-aos="fade-right")
              p.fw-bold Año 2. Cobro del interés explícito
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 15.
                span Registro contable por emisión de valores representativos de deuda a largo plazo
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Valores representativos de deuda a largo plazo
                      td.text-end $25.441,89
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Ingresos de valores representativos de deuda
                      td.text-end -
                      td.text-end $25.441,89
            .col-lg-4.mb-4.mb-lg-0.mx-auto.order-1.order-lg-2(data-aos="fade-right")
              img(src="@/assets/curso/tema1/img-24.svg" style="max-width: 298px").mx-auto
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-lg-7.mb-4.mb-lg-0.ps-lg-4.order-2.order-lg-1(data-aos="fade-right")
              p.fw-bold Año 2. Devengo del interés implícito
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 16.
                span Año 1. Devengo del interés implícito
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Valores representativos de deudas a corto plazo
                      td.text-end $390.441,89
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Valores representativos de deudas a largo plazo
                      td.text-end -
                      td.text-end $390.441,89
            .col-lg-5.mb-4.mb-lg-0.mx-auto.order-1.order-lg-2(data-aos="fade-right")
              img(src="@/assets/curso/tema1/img-25.svg" style="max-width: 298px").mx-auto
          .d-flex.flex-wrap.col-xl-11.mx-auto
            .col-lg-7.mb-4.mb-lg-0.ps-lg-4.order-2.order-lg-1(data-aos="fade-right")
              p.fw-bold Año 2. Reembolso de los títulos
              .titulo-sexto.color-acento-contenido.mb-3
                h5 Tabla 17.
                span Reclasificación de los títulos a corto plazo
              .tabla-a.mb-4(data-aos="fade-up")
                table.table-type-1
                  thead
                    tr
                      th(colspan="2") Cuenta
                      th Débitos
                      th Créditos
                  tbody
                    tr
                      td.text-start(colspan="2") Bancos
                      td.text-end $10.920,00
                      td.text-end -
                    tr
                      td.text-start(colspan="2") Ingresos de valores representativos de deuda
                      td.text-end -
                      td.text-end $10.920,00
            .col-lg-5.mb-4.mb-lg-0.mx-auto.order-1.order-lg-2(data-aos="fade-right")
              img(src="@/assets/curso/tema1/img-26.svg" style="max-width: 298px").mx-auto

    separador

    #t_1_7.titulo-segundo.color-acento-contenido
      h2 1.7 Reconocimiento, medición, presentación, revelación
    p.mb-5 En el presente ítem se abordan conceptos que determinan el reconocimiento de los instrumentos de patrimonio; a su vez, presenta ejemplos que acompañan el proceso de aplicabilidad.

    .row.mb-5.ajuste-espacios-movil.pt-5
      .col-xl
        TabsA.color-acento-botones.mb-4
          .tarjeta.color-acento-botones--borde.p-4(titulo="Reconocimiento")
            h4 Reconocimiento
            .d-flex.flex-wrap.align-items-center.gap-3
              p.order-2.order-md-1.col-12.col-md La entidad reconocerá un instrumento financiero en sus informes financieros cuando se convierta en parte del contrato o negocio jurídico conforme a las disposiciones de este.
              img.mx-auto.order-1.order-md-2(src="@/assets/curso/tema1/img-27.svg", alt="", style="max-width: 155px").m-auto
          .tarjeta.color-acento-botones--borde.p-4(titulo="Medición inicial")
            h4 Medición inicial
            .d-flex.flex-wrap.align-items-center.gap-3
              p.order-2.order-md-1.col-12.col-md Los activos y los pasivos financieros se valoran inicialmente por su valor razonable, que es el precio del hecho económico salvo evidencia en contrario.
              img.mx-auto.order-1.order-md-2(src="@/assets/curso/tema1/img-28.svg", alt="", style="max-width: 155px").m-auto
          .tarjeta.color-acento-botones--borde.p-4(titulo="Medición posterior")
            h4 Medición posterior
            .d-flex.flex-wrap.align-items-center.gap-3
              p.order-2.order-md-1.col-12.col-md Es la forma de reconocer en los estados financieros de manera posterior, el importe del instrumento con el reconocimiento de los ajustes correspondientes dependiendo de la forma como es reconocido y medido el título.
                br
                br
                |La medición se efectúa de acuerdo con el modelo de negocio del suscriptor. A valor razonable con cambios en el resultado del ejercicio, a costo amortizado con el interés efectivo y a valor razonable con cambios en el patrimonio de la sociedad. 
              img.mx-auto.order-1.order-md-2(src="@/assets/curso/tema1/img-29.svg", alt="", style="max-width: 155px").m-auto
          .tarjeta.color-acento-botones--borde.p-4(titulo="Presentación")
            h4 Presentación
            .d-flex.flex-wrap.align-items-center.gap-3
              p.order-2.order-md-1.col-12.col-md El emisor del título lo presentará clasificándolo en sus estados financieros totalmente o en la parte correspondiente, como un pasivo financiero, un activo financiero o un instrumento de patrimonio, de conformidad con las definiciones y características del hecho económico.
              img.mx-auto.order-1.order-md-2(src="@/assets/curso/tema1/img-30.svg", alt="", style="max-width: 155px").m-auto


    .d-flex.flex-wrap.mb-5
      .col-lg-7.mb-4.mb-lg-0.order-2.order-lg-1(data-aos="fade-right")
        p.p-4.mb-4(style="background-color: #F3F0EA") #[b Ejemplo:]
          br
          br
          |La sociedad contable SAS consultores adquiere un préstamo para compra de una propiedad inmobiliaria, por un valor de $128.000.000, le descuentan $400.000 para gastos de estudio del crédito. La tasa pactada es del 18 % EA, con pago a 5 cuotas anuales iguales.
        p Calculamos el valor de la cuota utilizando la herramienta pago en funciones financieras:
          br
          br
          | = Pago
          br
          | = $ 40.468.926,49
      .mx-auto.col-md-7.col-lg-5.order-1.order-lg-2
        img(src="@/assets/curso/tema1/img-31.png", alt="", style="max-width: 505px").mx-auto.mb-4.ps-lg-4   

    .titulo-sexto.color-acento-contenido.mb-3
      h5 Tabla 18.
      span Amortización contractual 

    p Para el reconocimiento de los abonos a capital e intereses incluidos en cada cuota por pagar.

    .tabla-a.mb-5(data-aos="fade-right")
      table.table-type-1(style="min-width: 850px")
        thead
          tr
            th Años
            th Saldo inicial
            th Cuota
            th Abono a intereses
            th Abono a capital
            th Saldo final
        tbody
          tr
            td 1
            td.text-end $128.000.000
            td.text-end $40.468.926
            td.text-end $22.400.000
            td.text-end $18.068.926
            td.text-end $109.931.074
          tr
            td 2
            td.text-end $109.931.074
            td.text-end $40.468.926
            td.text-end $19.237.938
            td.text-end $21.230.989
            td.text-end $88.700.085
          tr
            td 3
            td.text-end $88.700.085
            td.text-end $40.468.926
            td.text-end $15.522.515
            td.text-end $24.946.412
            td.text-end $63.753.673
          tr
            td 4
            td.text-end $63.753.673
            td.text-end $40.468.926
            td.text-end $11.156.893
            td.text-end $29.312.034
            td.text-end $34.441.640
          tr
            td 5
            td.text-end $34.441.640
            td.text-end $40.468.926
            td.text-end $6.027.287
            td.text-end $34.441.640
            td.text-end -

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/img-title.svg" style="max-width: 70px").m-auto
      .col
        h3 Reconocimiento inicial
    
    p.mb-5 La siguiente tabla presenta el registro contable correspondiente al reconocimiento inicial de una obligación financiera:
    .titulo-sexto.color-acento-contenido.mb-3
      h5 Tabla 19.
      span Reconocimiento inicial
    .tabla-a(data-aos="fade-left")
      table.table-type-1
        thead
          tr
            th Cuenta
            th Débito
            th Crédito
        tbody
          tr
            td.text-start Obligaciones financieras
            td.text-end -
            td.text-end $128.000.000,00
          tr
            td.text-start Costo amortizado
            td.text-end $400.000,00
            td.text-end -
          tr
            td.text-start Efectivo
            td.text-end $127.600.000,00
            td.text-end -


</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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

<style lang="sass">
.bg-gradient-1
  background: linear-gradient(0deg, #F3F0EA 0%, transparent 100%)
  margin-right: -3rem
  margin-left: -3rem
  padding-right: 3rem
  padding-left: 3rem
</style>
