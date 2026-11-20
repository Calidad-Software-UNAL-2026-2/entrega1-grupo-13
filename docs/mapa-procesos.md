# Mapa de Procesos y Modelo de Ciclo de Vida

> Generado con el workflow de flujo único. La definición formal del
> modelo de ciclo de vida (justificación, orden, relación entre
> procesos) se documenta en la wiki, página `04c-Modelo-Ciclo-Vida`,
> no en este archivo.

## Proceso: T02 — Definición de necesidades y requisitos de las partes interesadas

- **Entradas:** Modelo verbal extendido, necesidades de negocio, lista de interesados y escenarios de emergencia
- **Actividades:** Identificar y analizar las necesidades de los interesados; describir escenarios y condiciones de uso; formular y priorizar los requisitos de los interesados; resolver ambigüedades, validar requisitos y establecer trazabilidad
- **Salidas:** Especificación de requisitos de los interesados, concepto de operación y matriz de trazabilidad
- **Recursos:** Equipo de desarrollo, Analista de calidad / mejora continua, Ciudadano (usuario de la app), Ciudadano con discapacidad, Administrador del sistema, Autoridades / organismos gubernamentales, Adquiriente / entidad contratante y herramientas de documentación

## Proceso: T03 — Definición de requisitos del sistema y del software

- **Entradas:** Requisitos de los interesados, concepto de operación, restricciones y servicios externos identificados
- **Actividades:** Definir funcionalidades, interfaces y reglas del sistema; especificar los atributos y criterios de calidad; revisar la consistencia, viabilidad y verificabilidad de los requisitos; mantener la trazabilidad y controlar sus modificaciones
- **Salidas:** Especificación de requisitos del sistema y del software, criterios de aceptación y matriz de trazabilidad
- **Recursos:** Equipo de desarrollo, Analista de calidad / mejora continua, Administrador del sistema, Autoridades / organismos gubernamentales, Adquiriente / entidad contratante y documentación de interfaces externas

## Proceso: T06 — Análisis del sistema

- **Entradas:** Problemas técnicos, requisitos, alternativas, modelos y criterios de evaluación
- **Actividades:** Definir los objetivos y criterios del análisis; preparar y ejecutar simulaciones o pruebas de concepto; analizar resultados, limitaciones y riesgos; documentar conclusiones y recomendaciones
- **Salidas:** Informes de análisis técnico y resultados de pruebas de concepto
- **Recursos:** Equipo de desarrollo, Analista de calidad / mejora continua, Equipo de soporte y mantenimiento, herramientas de simulación y datos de prueba

## Proceso: T04 — Definición de la arquitectura

- **Entradas:** Requisitos del sistema, atributos de calidad, restricciones, servicios externos e informes de análisis técnico y resultados de pruebas de concepto
- **Actividades:** Identificar los componentes y sus responsabilidades; definir las interfaces y mecanismos de comunicación; evaluar alternativas frente a los requisitos de calidad; seleccionar y documentar las decisiones arquitectónicas
- **Salidas:** Documento de arquitectura, vistas de componentes y registro de decisiones arquitectónicas
- **Recursos:** Equipo de desarrollo, Analista de calidad / mejora continua, Equipo de soporte y mantenimiento, herramientas de modelado y documentación de servicios externos

## Proceso: T05 — Definición del diseño

- **Entradas:** Arquitectura, requisitos del sistema, interfaces y restricciones técnicas
- **Actividades:** Detallar los componentes y flujos de información; diseñar las interfaces móviles y administrativas; definir modelos de datos y reglas de funcionamiento; revisar y documentar el diseño frente a los requisitos
- **Salidas:** Diseño detallado, modelos de datos y prototipos de interfaces
- **Recursos:** Equipo de desarrollo, Analista de calidad / mejora continua, Administrador del sistema, Ciudadano (usuario de la app), Ciudadano con discapacidad y herramientas de modelado

## Proceso: T07 — Implementación

- **Entradas:** Diseño detallado, requisitos asignados, interfaces y estándares de desarrollo
- **Actividades:** Preparar los entornos de desarrollo; implementar los componentes móviles, backend y panel administrativo; ejecutar pruebas unitarias y corregir defectos; versionar y documentar los componentes construidos
- **Salidas:** Código fuente versionado, componentes ejecutables y evidencias de pruebas unitarias
- **Recursos:** Equipo de desarrollo, Analista de calidad / mejora continua, Git/GitHub, herramientas de programación y entornos de desarrollo

## Proceso: T08 — Integración

- **Entradas:** Componentes implementados, especificaciones de interfaces, servicios externos y entorno de integración
- **Actividades:** Definir el orden y los criterios de integración; conectar los componentes internos y servicios externos; probar los flujos de recepción, validación y notificación; corregir incompatibilidades y documentar los resultados
- **Salidas:** Versión integrada, registros de integración y reporte de incompatibilidades
- **Recursos:** Equipo de desarrollo, Analista de calidad / mejora continua, Equipo de soporte y mantenimiento, entornos de integración y servicios externos del sistema

## Proceso: T09 — Verificación

- **Entradas:** Requisitos verificables, versión del sistema, criterios de aceptación y entorno de pruebas
- **Actividades:** Diseñar casos de prueba asociados a los requisitos; ejecutar pruebas funcionales y no funcionales; comparar los resultados con los criterios establecidos; registrar defectos y comprobar las correcciones
- **Salidas:** Plan e informe de verificación, evidencias de pruebas y registro de defectos
- **Recursos:** Analista de calidad / mejora continua, Equipo de desarrollo, Equipo de soporte y mantenimiento, herramientas de pruebas y dispositivos móviles

## Proceso: T10 — Transición

- **Entradas:** Versión verificada, entorno de destino, criterios de puesta en servicio y procedimientos de soporte
- **Actividades:** Preparar la infraestructura y el entorno piloto; instalar, configurar y comprobar el funcionamiento del sistema; preparar la documentación y orientar a los responsables de operación; establecer contingencias y formalizar la transición
- **Salidas:** Versión desplegada, plan y registros de transición y documentación operativa
- **Recursos:** Equipo de desarrollo, Equipo de soporte y mantenimiento, Administrador del sistema, Analista de calidad / mejora continua, Adquiriente / entidad contratante e infraestructura en la nube

## Proceso: T11 — Validación

- **Entradas:** Necesidades de los interesados, escenarios de uso, versión evaluable y criterios de validación
- **Actividades:** Preparar escenarios y simulaciones representativas; evaluar la recepción de alertas y el reporte de emergencias; observar la gestión de reportes y evaluar usabilidad y accesibilidad; analizar resultados y documentar las decisiones de aceptación
- **Salidas:** Plan e informe de validación, resultados de pruebas con usuarios y registro de observaciones
- **Recursos:** Ciudadano (usuario de la app), Ciudadano con discapacidad, Administrador del sistema, Autoridades / organismos gubernamentales, Equipo de desarrollo, Analista de calidad / mejora continua y Adquiriente / entidad contratante

## Proceso: T12 — Operación

- **Entradas:** Sistema desplegado, informe de validación del piloto, procedimientos operativos, indicadores y planes de continuidad
- **Actividades:** Supervisar el funcionamiento y rendimiento de la plataforma; gestionar alertas y reportes desde el panel administrativo; registrar y atender incidentes operativos y PQRS; aplicar contingencias y generar informes de operación
- **Salidas:** Registros e informes de operación, incidentes y solicitudes atendidas
- **Recursos:** Administrador del sistema, Equipo de soporte y mantenimiento, Analista de calidad / mejora continua, Autoridades / organismos gubernamentales, panel administrativo y herramientas de monitoreo

## Proceso: T13 — Mantenimiento

- **Entradas:** Reportes de defectos, solicitudes de mantenimiento, PQRS, registros operativos y versión vigente
- **Actividades:** Registrar, clasificar y diagnosticar incidencias; evaluar y priorizar las modificaciones necesarias; implementar correcciones y ejecutar pruebas de regresión; liberar versiones actualizadas y documentar los cambios
- **Salidas:** Versiones corregidas, registros de mantenimiento y evidencias de pruebas de regresión
- **Recursos:** Equipo de soporte y mantenimiento, Equipo de desarrollo, Analista de calidad / mejora continua, Administrador del sistema, Git/GitHub y herramientas de seguimiento de incidencias

