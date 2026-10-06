# Revisión contra el sílabo aprobado (paso 3)

**Documento de referencia:** Plan docente ADMI_5077 Gestión de Proyectos, OCT/2026 – FEB/2027, aprobado por la Dirección de Carrera de Computación.
**Datos revisados:** `datos/silabo.js`, versión 1.0.0 (5 de octubre de 2026).
**Revisó:** Claude (borrador) · **Debe validar:** Ing. Marco Patricio Abad Espinoza.

## 1. Lo que coincide sin cambios

| Elemento | Estado |
|---|---|
| 16 semanas, unidades, contenidos, actividades y horas (2 + 1 + 3 por semana; 32/16/48 = 96 h) | Coincide |
| Fechas de semanas, derivadas de «Fechas importantes» (semana 2 = 12/10/2026; semana 12 = 21/12/2026 – 03/01/2027) | Coincide |
| Fechas importantes de ambos bimestres (8 entradas) | Coincide |
| Ponderaciones de evaluación: 35 / 35 / 30 % en cada bimestre; cada componente suma su porcentaje | Coincide |
| Horario del paralelo A (lunes 11:00–13:00, aula 10402; martes 12:00–13:00, Zoom) | Coincide |
| Política de recuperación y texto de adaptaciones curriculares | Copiados literalmente, sin paráfrasis |
| Resultados de aprendizaje de la asignatura (4) | Copiados literalmente |
| Enlaces externos: todos provienen del plan docente | Sin enlaces inventados |

## 2. Decisiones tomadas al construir el sitio

| # | Qué | Decisión | Motivo |
|---|---|---|---|
| D1 | Enlace al documento ISO 21502 (hmoftakhari.com) | **No se publica.** Recurso marcado «Enlace en revisión». | Es una copia de una norma ISO con derechos en un sitio de terceros; la guía exige solo enlaces autorizados. Sugerencia: acceso vía biblioteca UTPL o la vista previa oficial en iso.org. |
| D2 | Teléfono y extensión institucional (073701444 ext. 2520) | No se publica; contacto por correo institucional y tutoría. | Regla de la guía: el contacto va por canales institucionales escritos; evita llamadas fuera de horario. Puede añadirse si el docente lo decide. |
| D3 | Erratas ortográficas del plan («gesion», «introdutoria», «Estilios orgnizacionales», «enfique», etc.) | Corregidas. | No alteran el contenido; mejoran la lectura. |
| D4 | Contenido 1.5, semana 1: «ISO 21520:2020» | Se escribe **ISO 21502:2020**. | La norma de gestión de proyectos es la 21502:2020; la propia semana 2 usa «ISO 21502». **Confirmar.** |
| D5 | Semana 3, contenido 2.5: «VAor ganado, ROI» | Se escribe «valor ganado, ROI». | Texto ambiguo; podría referirse a **VAN** (valor actual neto), más propio de la selección de proyectos. **Confirmar.** |
| D6 | Semana 10, contenido 7.4: «Modelos de desarrollo de 7.1quipos (Tuckman)» | «Modelos de desarrollo de equipos (Tuckman)». | Error de edición evidente. |
| D7 | Semana 15 aparece como «Unidad 4: El futuro…» con numeración 4.2.x | Se muestra sin número de unidad. | La unidad 4 es Gestión del cronograma (semana 7). **Confirmar el número correcto (¿Unidad 12?).** |
| D8 | Actividades del 2.º bimestre sin fecha (foros, clase presencial, escenarios experimentales 25 %, talleres) | Se indica «se programan en el aula virtual». | No se inventan fechas. |

## 3. Discrepancias abiertas en el plan docente (para el docente)

Estas no se corrigieron en el sitio porque cambian el contenido académico; el sitio muestra lo que dice el plan.

1. **Ediciones del PMBOK.** La bibliografía básica es la 7.ª edición (2021), pero la semana 1 cita la 6.ª edición (capítulo 3) y las semanas 9–12 citan «capítulos 8, 10 y 11», que corresponden a la estructura de la 6.ª edición (la 7.ª no tiene capítulos por área de conocimiento).
2. **Semana 10:** la lectura «PMBOK capítulo 8» repite el capítulo de calidad de la semana 9; en la 6.ª edición, recursos es el capítulo 9.
3. **Semana 7:** la tutoría dice «dudas sobre la elaboración del presupuesto», pero el tema es el cronograma (costos es la semana 8).
4. **Semanas 3, 8 y 15:** el resultado de aprendizaje «Conoce las principales metodologías para la gestión de proyectos» no está entre los cuatro resultados oficiales de la asignatura (el más cercano es «Conoce las principales fases y áreas de conocimientos…»).
5. **Semana 8, autónomo:** «Repase los contenidos de las unidades 1 y 2», aunque el examen bimestral cubre hasta la unidad 5.
6. **Numeración repetida:** 1.4 y 1.5 (semanas 1 y 2), 2.5 (semanas 3 y 4), 3.1–3.4 (semanas 5 y 6).
7. **Semana 16** menciona «examen bimestral» y «examen final»; aclarar si son la misma evaluación.
8. **Segundo bimestre, evaluación:** «Taller grupal» sin ponderación (formativa) y «Actividad presencial» sin modalidad.
9. **Feriados:** el lunes 2 de noviembre de 2026 (Día de Difuntos) cae en la semana 5; la semana 12 incluye Navidad y Año Nuevo. Confirmar la recuperación de clases con el calendario académico UTPL.

## 4. Recursos sin enlace en el plan

PMBOK 6.ª ed., López Miranda, guía didáctica, Scrum Guide (2020), Manifiesto Ágil y Sutherland (2014) se muestran con la etiqueta **«En el aula virtual»** y sin enlace. Si el docente desea enlazar fuentes abiertas oficiales (por ejemplo, la Scrum Guide o el Manifiesto Ágil), debe añadirlas en `datos/silabo.js` tras verificarlas.

## 5. Aviso de la lista de tareas

Verificado en la sección «Mis tareas»: *«Marcar aquí no entrega la tarea. Las entregas se hacen en el aula virtual (EVA)… no crea un registro académico y se borra si limpia los datos del navegador».*

**Discrepancias abiertas: 9 (sección 3) + 3 por confirmar (D4, D5, D7).** El sitio puede publicarse como demostración; las correcciones se hacen solo en `datos/silabo.js`.
