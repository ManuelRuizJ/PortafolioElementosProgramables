
# Portafolio de Laboratorio de Elementos Programables

## Universidad Iberoamericana Puebla

Portafolio académico de la materia **Laboratorio de Elementos Programables**, correspondiente a la carrera de Ingeniería en Sistemas Computacionales. Este repositorio reúne los reportes, ejercicios, códigos, simulaciones y evidencias desarrollados durante el curso.

El trabajo se enfoca en el aprendizaje de sistemas electrónicos programables mediante el uso de microcontroladores, principalmente Arduino Uno y ATtiny85. A través de diferentes prácticas se exploró cómo conectar componentes electrónicos, programar entradas y salidas, procesar señales y controlar dispositivos externos mediante instrucciones de código.

---

## Objetivo del portafolio

Documentar las actividades realizadas durante el laboratorio y mostrar la aplicación práctica de los conocimientos relacionados con la programación de microcontroladores y la integración de componentes electrónicos.

Los ejercicios permiten comprender la relación entre el software y el hardware: el programa define el comportamiento del microcontrolador, mientras que los sensores, botones, luces, motores y demás componentes permiten interactuar con el entorno físico.

## Temas y conocimientos trabajados

Durante las prácticas documentadas se abordaron los siguientes temas:

- **Introducción a los sistemas programables:** funcionamiento general de los microcontroladores y su aplicación en sistemas electrónicos.
- **Arduino Uno:** identificación de sus componentes, configuración y utilización como plataforma de desarrollo.
- **Entradas y salidas digitales:** lectura de señales de entrada y control de dispositivos mediante estados HIGH y LOW.
- **Entradas analógicas:** lectura de valores variables provenientes de componentes como los potenciómetros y sensores.
- **Control de tiempo:** utilización de retardos para establecer intervalos y secuencias de ejecución.
- **Estructuras de control:** uso de condiciones `if`, `else`, operadores lógicos y variables para modificar el comportamiento de los circuitos.
- **ATtiny85:** programación de un microcontrolador de menor tamaño y recursos limitados.
- **PWM:** generación de señales para regular el comportamiento de componentes electrónicos.
- **Sensores:** identificación y clasificación de sensores digitales, analógicos e inteligentes.
- **Actuadores:** control de LEDs, zumbadores, servomotores, motores DC y tiras NeoPixel.
- **Simulación y documentación:** elaboración de circuitos, pruebas, códigos y reportes de resultados.

---

## Prácticas realizadas

### 1. Introducción a Arduino

**Fecha:** 16 de agosto de 2023.

Primera aproximación al desarrollo de circuitos electrónicos utilizando Arduino Uno. Se trabajó con los conceptos básicos de programación de microcontroladores, conexión de componentes y configuración de entradas y salidas.

Se documentaron ejercicios de programación y simulación para comprender cómo las instrucciones ejecutadas por Arduino producen cambios en los componentes conectados.

**Actividades desarrolladas:**

- Ejemplo Blink para controlar el encendido y apagado de un LED.
- Configuración de salidas digitales mediante `HIGH` y `LOW`.
- Uso de retardos para controlar tiempos de ejecución.
- Conexión y control de LEDs.
- Construcción de circuitos utilizando una protoboard.
- Control de varios LEDs.
- Manejo de un display de siete segmentos.
- Implementación de un contador digital.
- Lectura de botones como entradas digitales.
- Uso de condiciones para modificar el comportamiento del circuito.
- Aplicación de operadores lógicos en las condiciones de entrada.

**Componentes principales:** Arduino Uno, protoboard, cables, resistencias, LEDs, botones y display de siete segmentos.

### 2. Arduino básico II: servomotores y potenciómetros

**Fecha:** 30 de agosto de 2023.

En esta práctica se amplió el trabajo con Arduino mediante la integración de componentes capaces de modificar su comportamiento de acuerdo con las señales recibidas.

Se trabajó principalmente con servomotores y potenciómetros, explorando cómo leer valores de entrada y utilizarlos para controlar el movimiento de dispositivos.

**Actividades desarrolladas:**

- Control básico de un servomotor.
- Control de servomotores mediante diferentes configuraciones.
- Lectura de valores de un potenciómetro.
- Visualización de valores mediante comunicación serial.
- Control de varios servomotores.
- Inversión del sentido o comportamiento de los servomotores.
- Control independiente de dos servomotores.
- Integración de servomotores y LEDs.
- Ejercicios de control mediante diferentes valores de entrada.

**Componentes principales:** Arduino Uno, protoboard, LEDs, servomotores, potenciómetros, cables y resistencias.

### 3. Introducción al microcontrolador ATtiny85

**Fecha:** 6 de septiembre de 2023.

En esta práctica se comenzó a trabajar con el microcontrolador ATtiny85, perteneciente a la familia AVR de 8 bits. Se estudió su funcionamiento y sus características como alternativa para desarrollar sistemas electrónicos compactos.

Se realizaron ejercicios para comprender cómo configurar sus pines y programar diferentes comportamientos utilizando el entorno de desarrollo de Arduino.

**Actividades desarrolladas:**

- Configuración del ATtiny85.
- Uso de Arduino Uno como programador ISP.
- Ejemplo Blink con ATtiny85.
- Configuración de salidas digitales.
- Encendido y apagado de LEDs.
- Control de retardos.
- Manejo de varios LEDs.
- Lectura de entradas digitales.
- Uso de condiciones `if` y `else`.
- Aplicación de variables y operadores lógicos `OR` y `AND`.
- Implementación de contadores utilizando LEDs.

**Componentes principales:** Arduino Uno, ATtiny85, protoboard, resistencias, LEDs, botones y cables.

### 4. Control de actuadores con ATtiny85

**Fecha:** septiembre de 2023.

Se continuó trabajando con el ATtiny85, ampliando los ejercicios de control de componentes electrónicos. La práctica se enfocó en combinar entradas digitales con diferentes actuadores para generar respuestas dependiendo de las condiciones programadas.

**Actividades desarrolladas:**

- Control de LEDs mediante botones.
- Implementación de secuencias de encendido y apagado.
- Activación de un buzzer.
- Control de LEDs RGB.
- Implementación de contadores con LEDs RGB.
- Control de motores DC.
- Uso de señales PWM para regular salidas.
- Control de buzzer mediante PWM.
- Control de servomotores.
- Activación de servomotores mediante botones.
- Integración de LEDs direccionables NeoPixel.
- Control de tiras de LEDs NeoPixel.
- Combinación de botones y actuadores en un mismo circuito.

**Componentes principales:** ATtiny85, Arduino Uno, LEDs, LEDs RGB, buzzer, motor DC, servomotores, botones y componentes NeoPixel.

### 5. Lectura de entradas y sensores con ATtiny85

**Fecha:** 4 de octubre de 2023.

Esta práctica se enfocó en el uso de sensores como elementos de entrada para los sistemas programables. Se trabajó con señales digitales y analógicas para comprender cómo un microcontrolador puede recibir información del entorno y utilizarla dentro de un programa.

**Actividades desarrolladas:**

- Lectura de sensores digitales.
- Lectura de sensores analógicos.
- Detección de estados de encendido y apagado.
- Uso de condiciones para interpretar las señales recibidas.
- Aplicación de retardos en la lectura y procesamiento de entradas.

**Ejercicios documentados:**

- Sensor digital con comportamiento ON/OFF.
- Sensor analógico con comportamiento ON/OFF.
- Lectura de sensor analógico con retardo.

**Componentes principales:** ATtiny85, Arduino Uno, protoboard, sensores, potenciómetros, LEDs, botones y resistencias.

### 6. Investigación y clasificación de sensores

**Fecha:** 25 de octubre de 2023.

En esta actividad se realizó una investigación sobre diferentes sensores utilizados en sistemas electrónicos y proyectos de automatización.

Se documentaron distintos modelos, su función, el tipo de magnitud que permiten medir y la clasificación de sus señales.

Entre los sensores investigados se encuentran:

| Sensor | Aplicación |
|---|---|
| DS18B20 | Medición de temperatura |
| LDR | Detección de intensidad luminosa |
| DHT22 | Medición de temperatura y humedad |
| PIR | Detección de movimiento |
| MQ-7 | Detección de monóxido de carbono |
| BMP180 | Medición de presión barométrica |
| KY-037 | Detección de sonido |
| KY-017 | Detección de inclinación |
| TCS230 | Detección de color |
| Sensor de nivel de agua | Detección de nivel de líquidos |
| Sensor Flex | Detección de flexión |
| Encoder | Medición de velocidad o posición |
| Sensor de vibración | Detección de vibraciones |
| KY-026 | Detección de llama |
| MAX30102 | Medición de señales relacionadas con el pulso |
| ADXL345 | Medición de aceleración |
| Sensor UV | Detección de radiación ultravioleta |
| KY-032 | Detección de obstáculos |
| SCT-013 | Medición de corriente eléctrica |
| AD8232 | Adquisición de señales ECG |
| Sensor PM2.5 | Medición de partículas en el aire |
| Sensor de campo magnético | Detección de campos magnéticos |
| KY-024 | Detección de campos magnéticos |
| KY-023 | Lectura de movimiento mediante joystick |
| ML8511 | Medición de radiación ultravioleta |
| KY-018 | Detección de intensidad luminosa |

La actividad permitió conocer la variedad de sensores disponibles y sus posibles aplicaciones en sistemas de monitoreo, automatización y control.

---

## Herramientas y tecnologías

Las herramientas y componentes identificados en los reportes incluyen:

| Herramienta o componente | Utilización |
|---|---|
| Arduino Uno | Plataforma para programación y experimentación con microcontroladores. |
| ATtiny85 | Microcontrolador utilizado en ejercicios de entradas, salidas y control. |
| Arduino IDE | Entorno de programación para desarrollar código de microcontroladores. |
| Tinkercad | Simulación y experimentación con circuitos electrónicos. |
| Protoboard | Construcción y conexión de circuitos. |
| LEDs y LEDs RGB | Representación visual de estados y señales. |
| Servomotores | Control de movimiento y posición. |
| Motor DC | Experimentación con actuadores. |
| Potenciómetros | Generación de señales de entrada variables. |
| Buzzer | Generación de señales sonoras. |
| Sensores | Obtención de información del entorno físico. |
| NeoPixel | Control de LEDs direccionables. |

## Organización del repositorio

El repositorio está organizado para separar el portafolio principal de los reportes individuales de cada práctica.

```text
PortafolioElementosProgramables/
│
├── README.md
├── index.html
│
├── assets/
│   └── Recursos generales del portafolio
│
├── css/
│   └── styles.css
│
├── js/
│   └── scripts.js
│
├── img/
│   └── Imágenes del portafolio
│
├── practica1/
│   ├── index.html
│   ├── assets/
│   ├── css/
│   ├── files/
│   ├── img/
│   ├── js/
│   └── video/
│
├── practica2/
├── practica3/
├── practica4/
├── practica5/
└── practica7/
```

Cada carpeta de práctica contiene su propia página de documentación y recursos asociados, como imágenes, archivos y evidencias de los ejercicios.

## Portafolio web

Además de los reportes individuales, se desarrolló una página web para presentar las actividades de manera organizada y facilitar su consulta.

La página principal incluye:

- Presentación del portafolio y de la materia.
- Información académica del estudiante.
- Sección de prácticas realizadas.
- Tarjetas para identificar cada actividad.
- Enlaces para consultar los reportes individuales.
- Organización de imágenes y recursos visuales.

Para su elaboración se utilizaron tecnologías de desarrollo web como:

- HTML5 para la estructura de las páginas.
- CSS3 para los estilos y presentación visual.
- JavaScript para funcionalidades de la interfaz.
- Bootstrap para la organización y diseño responsivo.
- Bootstrap Icons para elementos gráficos.

## Aprendizajes obtenidos

El desarrollo de las actividades permitió relacionar la programación con el funcionamiento físico de los dispositivos electrónicos.

Entre los principales aprendizajes se encuentran:

1. Comprender la estructura y funcionamiento básico de una placa Arduino.
2. Programar microcontroladores para controlar componentes electrónicos.
3. Diferenciar entre entradas y salidas digitales y analógicas.
4. Utilizar condiciones y operadores lógicos para crear comportamientos.
5. Controlar actuadores como LEDs, motores, servomotores y buzzers.
6. Comprender el funcionamiento del PWM y sus aplicaciones.
7. Experimentar con el microcontrolador ATtiny85 y sus recursos.
8. Identificar diferentes tipos de sensores y sus aplicaciones.
9. Integrar componentes electrónicos para construir circuitos funcionales.
10. Documentar el proceso de desarrollo mediante reportes, códigos y evidencias.

## Evidencias

Los reportes individuales, las simulaciones, los códigos y los recursos de cada actividad se encuentran organizados en sus respectivas carpetas.

- [Práctica 1: Introducción a Arduino](practica1/)
- [Práctica 2: Arduino básico II](practica2/)
- [Práctica 3: ATtiny85](practica3/)
- [Práctica 4: Control de actuadores con ATtiny85](practica4/)
- [Práctica 5: Entradas y sensores con ATtiny85](practica5/)
- [Práctica 7: Sensores](practica7/)

## Autor

**Jesús Manuel Ruiz Fuentes**

Ingeniería en Sistemas Computacionales  
Universidad Iberoamericana Puebla

---

Este repositorio tiene fines académicos y reúne las evidencias documentadas durante el desarrollo de la materia de Laboratorio de Elementos Programables.
