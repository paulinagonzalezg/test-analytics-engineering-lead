---

# Ejercicios para Analytics Engineering Lead

Debe realizar un fork de este repositorio para desarrollar, documentar y entregar su trabajo.

Si está interesado en aplicar al test, puede enviar un correo a jguerrero@deacero.com.

## Ejercicio de Gestión

Tu equipo de Analytics Engineering está trabajando con un pipeline de datos clave para la organización que alimenta informes diarios utilizados por varias áreas de negocio. Sin embargo, el pipeline ha comenzado a fallar esporádicamente, provocando retrasos en la entrega de datos críticos. Las interrupciones no son constantes, pero cuando ocurren, generan importantes tiempos de inactividad y requieren intervención manual, lo que afecta la confianza en los datos.

El equipo tiene el 80% de su capacidad dedicada a tareas prioritarias de la unidad de negocio fuera de tu alcance, dejando solo el 20% disponible para abordar la optimización de este pipeline.

#### Objetivo:
Diseña una estrategia de optimización para este pipeline con el tiempo y recursos disponibles. Tu objetivo es reducir la frecuencia de fallos y minimizar el impacto en el tiempo de intervención manual, generando un uso eficiente de los recursos.

#### Información clave:
- El pipeline gestiona una gran cantidad de datos provenientes de múltiples fuentes.
- Las fallas ocurren esporádicamente debido a la latencia y a problemas con la calidad de los datos de algunas fuentes.
- Las intervenciones manuales actuales consisten en verificar logs y reiniciar el proceso cuando los datos fallan en cargarse correctamente.
- El equipo tiene acceso a herramientas de monitoreo básicas y logs, pero no hay automatización en el proceso de detección y resolución de problemas.
- Solo cuentas con un 20% del tiempo del equipo para esta optimización, por lo que debes priorizar las soluciones de mayor impacto.

## Ejercicio Práctico

Este ejercicio utiliza datos de una campaña de marketing por correo electrónico disponibles en el [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing). Los datos contienen información sobre diversas campañas de marketing directo de una institución bancaria.

**Objetivo:**

Crear y desplegar un Data Mart que permita al equipo de marketing analizar la efectividad de sus campañas, enfocándose en KPIs como la tasa de conversión, el número de contactos exitosos y la segmentación de clientes.

#### Información clave:

- El diseño de la arquitectura, capas y modelos de datos es a libre elección.
- La solución debe contemplar pruebas unitarias, mantener la calidad de los datos y desplegar modelos de datos en BigQuery
- Los datos se pueden obtener desde [Bank Marketing dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing).
- El modelo final debe calcular:
  - Tasa de conversión: porcentaje de contactos exitosos sobre el total de contactos.
  - Número de contactos exitosos: total de conversiones logradas.
  - Segmentación de clientes: clasificación de clientes basada en criterios relevantes como edad, ocupación, etc.
- Las pruebas unitarias minimas a contemplar son:
  - Validar tipos de datos.
  - Comprobar valores nulos.
  - Verificar rangos y unicidad de campos clave.
- Para el despliegue puede configurarse un pipeline CI/CD en cualquier herramienta que considere:
  - Validación de código.
  - Ejecución de pruebas unitarias.
  - Despliegue en BigQuery.
  - Configura alertas para pruebas fallidas y realiza auditorías periódicas de calidad de datos.

#### Entrega del Ejercicio

- Suba su proyecto a un repositorio de GitHub y comparta el enlace en un correo dirigido a jguerrero@deacero.com.
- Asegúrese de que el repositorio incluya:
    - Todos los recursos usados o generados para la solucion de los ejercicios.
    - Documentación que explique el proceso seguido, las decisiones tomadas.
    - Instrucciones claras sobre cómo configurar y ejecutar el proyecto y sus artefactos.


Suerte a todos!!! :metal: :nerd_face: :computer:

---
