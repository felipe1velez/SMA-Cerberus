# SMA-Cerberus
Final project Digi3

Nombre del proyecto: SMA Cerberus

Descripción General
SMA Cerberus es un sistema embebido de monitoreo ambiental en tiempo real, desarrollado sobre la plataforma Raspberry Pi Pico o Pico W. El proyecto está orientado a la medición y análisis de variables ambientales críticas como temperatura, humedad, calidad del aire, presión atmosférica y ruido ambiental. Su diseño modular y su conectividad permiten tanto la visualización local como remota, además de alertas configurables por el usuario.

Objetivo del Proyecto
Desarrollar un dispositivo capaz de monitorear parámetros ambientales clave de forma precisa, confiable y accesible, brindando alertas y registros que faciliten la toma de decisiones. El sistema está orientado a aplicaciones en hogares, industrias, instituciones educativas y espacios públicos, con una propuesta de bajo costo y amigable con el medio ambiente.

Características Principales

Medición ambiental en tiempo real:
  Temperatura y humedad (DHT11/DHT22 o BME280).
  Calidad del aire (MQ-135).
  Nivel de ruido ambiental (micrófono con amplificador).
  Presión atmosférica (BMP180 o BME280).

Alertas inteligentes:
  Alerta sonora (buzzer piezoeléctrico) y visual (LED RGB o display) ante valores     fuera de umbrales.
  Umbrales configurables por el usuario mediante teclado matricial o botones          físicos.

Interfaz de usuario:
    Visualización local mediante pantalla OLED/LCD.
    Menús de navegación para configuración e inspección de datos.

Conectividad:
    Transmisión de datos vía WiFi (Raspberry Pi Pico W) o Bluetooth (HC-05/HC-06).
    Consulta remota desde app móvil o navegador web.

Requisitos Funcionales
    Medición precisa y continua de todas las variables ambientales.
    Configuración de umbrales máximos y mínimos por parte del usuario.
    Activación de alertas ante valores críticos.
    Visualización de datos en tiempo real a nivel local.
    Transmisión de datos a plataforma móvil o web.
    Navegación e interacción mediante teclado matricial o botones.
    Consulta remota desde PC o smartphone.

Requisitos No Funcionales
    Confiabilidad: funcionamiento continuo sin fallos prolongados.
    Precisión: sensores calibrados dentro de márgenes aceptables.
    Usabilidad: interfaz intuitiva y fácil de manejar.
    Portabilidad: diseño compacto y transportable.
    Modularidad: arquitectura que permita cambios o ampliaciones sin rediseñar todo     el sistema.
    Escalabilidad: posible incorporación de sensores o funciones futuras.
    Bajo consumo energético: posibilidad de funcionamiento con batería.
    Tiempo de respuesta eficiente: reacciones rápidas ante eventos críticos.
    Compatibilidad de conectividad: integración con WiFi/Bluetooth estándar.
    Presentación estética: prototipo ordenado, funcional y con carcasa adecuada.

Escenarios de Prueba:
1. Pruebas en Laboratorio (LED):
  Simulación de temperatura y humedad con pistola de aire y recipientes con agua.
  Generación de contaminantes con incienso.
  Inducción de ruido ambiental con parlantes.
  Verificación de alertas, visualización local y transmisión remota de datos.

2. Pruebas en Campo (Cancha al aire libre):
  Medición directa de variables ambientales.
  Validación del sistema en condiciones reales.
  Prueba de conectividad remota y operación autónoma.

Presupuesto Estimado:

Costo Total Aproximado: $ 161,300  COP.

Financiamiento: Compartido por el equipo. Se reutilizarán componentes del laboratorio o proyectos anteriores cuando sea posible.	


Motivación del Proyecto
Elegimos desarrollar SMA Cerberus porque nos permite integrar y aplicar los conocimientos que adquiriremos en este curso, así como otros que estamos viendo, como Acondicionamiento de Señales, y los que ya hemos abordado en materias previas como Electrónica Analógica I y II, Circuitos I y II, entre otras. Además, nos brinda la oportunidad de fortalecer habilidades prácticas en diseño modular, programación y pruebas de sistemas en tiempo real, mediante un proyecto con impacto tanto técnico como ambiental.
