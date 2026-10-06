# Pruebas locales (paso 4)

**Fecha:** 5 de octubre de 2026 · **Herramienta:** Chromium (Playwright) sobre `index.html` local · **Datos:** `silabo.js` v1.0.0

Para simular cualquier fecha agregue `?hoy=AAAA-MM-DDTHH:MM` a la dirección, por ejemplo `index.html?hoy=2026-11-25T10:30`.

## Resultados automáticos

| Prueba | Condición | Resultado |
|---|---|---|
| Teléfono 375 px | Ancho total de la página | 375 px: **sin desplazamiento lateral** ✅ |
| Texto al 200 % | 375 px, todas las semanas abiertas | 375 px: **sin desplazamiento lateral ni solapamientos** ✅ (tras corregir cabecera, línea del semestre, chips y rejillas) |
| Escritorio 1280 px, modo oscuro | Contraste y lectura | Correcto ✅ |
| «Lo próximo» antes del semestre | `?hoy=2026-09-20` | «Empieza pronto», primera clase lunes 5 oct 11:00 ✅ |
| «Lo próximo» en semana 1 | `?hoy=2026-10-05T17:30` | Semana 1; próxima sesión tutoría martes 6 oct 12:00; próxima evaluación semana 2 ✅ |
| «Lo próximo» en semana 8 | `?hoy=2026-11-25T10:30` | Semana 8; evaluación esta semana: examen bimestral y escenarios ✅ |
| Semana 12 (dos semanas de calendario) | `?hoy=2026-12-28` | Semana 12 correcta ✅ |
| Fin del semestre | `?hoy=2027-02-10` | «Semestre concluido» ✅ |
| Errores de JavaScript | Todas las fechas | Ninguno ✅ (solo la fuente web bloqueada en el entorno de prueba; usa la fuente del sistema) |
| Lista de tareas | Marcar en «Mis tareas» | Se sincroniza con el cronograma y persiste tras recargar ✅ |
| Buscador | «semana 2» | Guía didáctica, video PRINCE2, ISO 21502 (en revisión) ✅ |
| Teclado | Orden de tabulación | Saltar al contenido → menú → Lo próximo → buscador → resultados → contacto → … ✅ Foco visible en todos los controles |

## Comprobaciones manuales pendientes (docente o colega)

- [ ] **Enlaces externos:** abrir cada enlace de «Lecturas y recursos» (el entorno de prueba no tiene acceso a esos dominios). El de Wysocki requiere credenciales UTPL.
- [ ] **Teléfono real:** un colega busca la lectura de la semana 2 en menos de 30 segundos.
- [ ] **Zoom del navegador al 200 %** en un teléfono real.
- [ ] **Lector de pantalla** (TalkBack o VoiceOver): la línea del semestre anuncia «Semana N, fechas, unidad».
- [ ] **Borrar datos del navegador:** la lista se reinicia y en ningún lugar se afirma que hubo entrega.
