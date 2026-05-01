# Edutek · Prototipo del reporte

Prototipo del sistema de reportería diagnóstica de lectoescritura **Edutek**, desarrollado en el marco del proyecto Innova de Ingeniería UC (ING2030).

## Páginas

- **`index.html`** — Landing comercial con descripción del producto y acceso al reporte.
- **`profesor.html`** — Reporte del curso para el profesor: distribución por nivel, movimientos entre evaluaciones, desempeño por sección, trayectoria por estudiante.

## Cómo navegar

Desde la landing (`index.html`), ir a la sección "Acceso al reporte". Las credenciales del demo vienen pre-llenadas; basta con presionar "Ingresar".

- Demo: `paola.munoz@loscondores.cl`

## El producto

Edutek **no** es una plataforma de intervención. Es un **sistema de reportería**. El flujo real:

1. El equipo Edutek aplica la prueba diagnóstica de lectoescritura en el colegio.
2. Las respuestas manuscritas se procesan y se clasifica a cada estudiante por nivel (Insuficiente / Elemental / Adecuado).
3. Se envía un **link al correo del profesor** con el reporte del trimestre.
4. El profesor abre el link y ve los resultados visualizados.
5. El ciclo se repite tres veces por semestre. Cada nuevo informe muestra la evolución acumulada.

El profesor **decide qué hacer con esa información**. Edutek entrega el diagnóstico, no la intervención.

## Notas técnicas

- HTML + CSS + JS vanilla, sin dependencias externas más allá de Google Fonts (Inter).
- Datos hardcodeados con fines de demo (30 estudiantes, 2 evaluaciones aplicadas + 1 proyectada).
- Se asume que la fecha actual es **22 de abril de 2026** para que coincida con el ciclo trimestral del demo.

## Equipo

Agustín · Valentina · Tomás · Cristóbal · Matilde
