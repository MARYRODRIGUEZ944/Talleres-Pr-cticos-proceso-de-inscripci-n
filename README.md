1. Resumen Ejecutivo

El presente informe técnico describe el modelado, análisis y optimización del proceso de inscripción académica intersemestral en la FESC, desarrollado bajo una metodología estructurada en cuatro fases: análisis, diseño, optimización y documentación técnica.
El objetivo principal fue identificar cuellos de botella, tareas manuales redundantes y oportunidades de automatización que permitan mejorar la eficiencia operativa y la experiencia del estudiante.

2. Análisis del Proceso Actual (AS-IS)

El proceso actual se caracteriza por la intervención manual de múltiples actores y la ausencia de validaciones automáticas en el sistema.
Los actores principales son:

Estudiante: inicia el proceso, selecciona materias y realiza pagos.

Sistema Académico: valida prerrequisitos y cupos.

Coordinación Académica: aprueba inscripciones especiales y excesos de cupo.

Docente: confirma la lista de estudiantes inscritos.

Tesorería: procesa pagos y genera comprobantes.

Principales limitaciones detectadas:

Validaciones manuales de prerrequisitos.

Procesos secuenciales que podrían ejecutarse en paralelo.

Falta de integración entre el sistema académico y la tesorería.

Comunicación tardía hacia docentes y estudiantes.

3. Proceso Optimizado (TO-BE)

El diagrama optimizado incorpora mejoras estructurales y funcionales:

Automatización: el sistema valida automáticamente cupos, pagos y prerrequisitos.

Paralelización: validaciones académicas y financieras pueden ejecutarse de forma simultánea.

Integración: comprobante único generado desde una pasarela de pago integrada.

Notificación automática: docentes reciben alertas en tiempo real sobre inscripciones.

Acceso inmediato: el estudiante obtiene acceso al aula virtual tras confirmación del pago.

El diseño UML se compone de 5 carriles horizontales (swimlanes) representando los actores principales.
Incluye 3 decisiones, 2 puntos Fork/Join y 1 señal de evento, garantizando un flujo coherente y controlado.

4. Métricas y Comparación
Métrica	AS-IS	TO-BE
Actividades totales	14	11
Puntos de decisión	5	3
Nivel de automatización	40%	85%
Tiempo promedio del proceso	2 días	4 horas
Intervención manual	Alta	Mínima

Resultados esperados:

Reducción del tiempo operativo en un 80%.

Disminución de errores humanos en validaciones y pagos.

Mejor trazabilidad de los datos entre sistemas.

Incremento en la satisfacción del estudiante por una experiencia fluida y digitalizada.

5. Conclusiones

El proceso optimizado representa un avance significativo hacia la transformación digital de la gestión académica.
La automatización de validaciones, la integración de la pasarela de pagos y la comunicación instantánea con docentes fortalecen la eficiencia y transparencia institucional.
El diagrama TO-BE propuesto constituye una base sólida para futuras mejoras del ecosistema académico de la FESC.
