# Edutek · Prototipo del dashboard

Prototipo funcional de la plataforma de diagnóstico e intervención lectoescritora **Edutek**, desarrollada en el marco del proyecto Innova de Ingeniería UC (ING2030).

## Páginas

- **`index.html`** — Landing comercial con acceso segmentado para profesores y directores.
- **`profesor.html`** — Dashboard del profesor: actividades de intervención por grupo, vista por estudiante, modo aula con timer, notas, marcar completadas, descargar PDF, resumen para apoderados.
- **`director.html`** — Dashboard del director / Jefe UTP: salud del establecimiento, comparativa entre cursos, alertas, reportes PME y SEP.

## Cómo navegar

Desde la landing (`index.html`), bajar a la sección "Para quién" y elegir el rol. Las credenciales del demo vienen pre-llenadas; basta con presionar "Ingresar".

- Profesor demo: `paola.munoz@loscondores.cl`
- Director demo: `carlos.pino@loscondores.cl`

## Notas técnicas

- HTML + CSS + JS vanilla, sin dependencias externas más allá de Google Fonts (Inter).
- El estado de actividades completadas y notas del profesor se guarda en `localStorage` del navegador. Cada usuario verá su propio estado.
- Los nombres de grupos en el modo proyector son editables y se guardan localmente.
- Se asume que la fecha actual es **22 de abril de 2026** (hardcodeada para alinear con el ciclo trimestral demo).

## Equipo

Agustín · Valentina · Tomás · Cristóbal · Matilde
