<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono='far fa-question-circle', titulo='Actividad didáctica')
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    #Actividad
      <Actividad :cuestionario="cuestionario"/>
</template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema: 'Microcontroladores y sensores',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> identificar los conceptos clave relacionados con el reconocimiento, medición, presentación y revelación de instrumentos financieros, conforme a la normativa contable vigente.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO.',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Qué norma internacional define cómo se deben reconocer y medir los instrumentos financieros?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'NIC 32.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'NIIF 9.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'NIIF 7.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'NIC 39.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto: '¿Qué representa un pasivo financiero?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Una obligación contractual de entregar dinero u otro activo financiero.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Un derecho contractual de recibir dinero.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Una acción ordinaria en otra entidad.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Un instrumento de capital.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto: '¿Qué representa un pasivo financiero?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Una obligación contractual de entregar dinero u otro activo financiero.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Un derecho contractual de recibir dinero.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Una acción ordinaria en otra entidad.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Un instrumento de capital.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Qué método se utiliza para calcular el costo amortizado de un pasivo?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Método contable ordinario.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Método de tasa de interés efectiva.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Método de flujo de efectivo libre.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Método de valor residual.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: '¿Cuál es el objetivo de la política contable?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Organizar las cuentas contables por códigos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Establecer criterios de reconocimiento, medición y revelación.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Definir los estados financieros consolidados.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Establecer la tasa de interés efectiva.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Cuál es la diferencia principal entre pasivo financiero e instrumento de patrimonio?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La fecha de vencimiento.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El tipo de mercado donde se negocian.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'La existencia de una obligación contractual de entregar activos.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'El tipo de moneda utilizada.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: '¿Qué instrumentos se miden generalmente a valor razonable?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Instrumentos mantenidos para negociar.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Todos los préstamos bancarios.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Pasivos contingentes.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Acciones ordinarias de sociedades anónimas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Qué debe revelarse en las notas a los estados financieros según la NIIF 7?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Solamente saldos bancarios',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Naturaleza, garantías, vencimientos y saldos pendientes de los pasivos',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'La utilidad neta esperada',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Los aportes de capital realizados',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Qué tipo de cuenta representa una acción preferencial si el emisor debe reembolsarla?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Pasivo financiero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Activo financiero',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Instrumento de patrimonio',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Pasivo contingente',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto: '¿Qué representa el Otro Resultado Integral (ORI)?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Partidas que no afectan el resultado neto del periodo pero sí el patrimonio.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'La suma de todos los activos financieros.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'El resultado neto antes de impuestos',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'El total de reservas estatutarias.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            'La NIIF 7 se enfoca en la revelación de instrumentos financieros.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto:
            'Todos los activos financieros deben medirse siempre a costo amortizado.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Verdadero',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto:
            'Un instrumento de patrimonio representa una participación residual en los activos de una entidad.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso ',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto:
            'Las provisiones se reconocen cuando hay certeza del monto y la fecha de pago.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Verdadero',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto:
            'El capital suscrito es la parte del capital autorizado que los accionistas se comprometen a pagar.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso ',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
