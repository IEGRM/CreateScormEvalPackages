# Generador de exámenes SCORM para Moodle

Para cualquier materia: matemáticas, cálculo, sistemas, ciencias o temas generales. Convierta su material en una prueba lista para Moodle, con módulo de seguridad, pantalla de envío y nota de 0 a 5. No necesita saber programar.

1

## Copie el prompt y llévelo a su IA

Péguelo en ChatGPT, Gemini, Claude o Copilot. En la parte **1. BASE DEL EXAMEN** deje una opción: crear preguntas con su archivo, usar las preguntas que ya trae su archivo, o pegar el contenido si no tiene archivo ni foto. Lo demás ya está listo.

Ver el prompt

2

## Pegue aquí la respuesta de la IA

Copie el bloque de código que le entregó la IA y péguelo completo. La revisión aparece debajo.

Aún no hay nada pegado.

3

## Revise los ajustes y descargue

Los ajustes se llenan solos con lo que escribió la IA. Cámbielos si lo necesita.

Título del examen Asignatura y grado Tiempo sugerido (minutos) Nota mínima para aprobar (0 a 5) Retroalimentación al final

[ ] Barajar el orden de las preguntas [x] Barajar las opciones de respuesta

## Al subirlo a Moodle

Agregue una actividad **Paquete SCORM**, suba el .zip sin descomprimirlo y deje estos ajustes:

| Ajuste | Valor |
| --- | --- |
| Grading method (Método de calificación) | Highest grade (Calificación más alta) |
| Maximum grade (Calificación máxima) | 5 |
| Number of attempts (Número de intentos) | 1 o 2 |
| Attempts grading (Calificación de intentos) | Highest attempt (Intento más alto) |
| Force new attempt / Force completed | No / No |
| Auto-commit | Yes |

Pruébelo con una cuenta de estudiante antes de publicarlo; el modo vista previa no guarda notas. Luego borre ese intento en Informes. El registro de salidas de pestaña de cada estudiante aparece en Informes, en el detalle del intento (campo cmi.comments).