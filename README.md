# Portal de miembros Hay Equipo (prototipo)

Prototipo navegable del portal de miembros de Hay Equipo: agenda, perfiles, directorio, novedades, pagos de la mensualidad, viajes, reuniones y panel de coordinación.

Es un solo archivo HTML, sin backend. Los datos son ficticios y los cambios se guardan en el navegador (localStorage).

## Cómo verlo

Abrí [`prototipo/index.html`](prototipo/index.html) en el navegador (doble clic). Necesita internet solo para las tipografías.

Arriba a la derecha, el selector **Ver como** cambia de persona:

- **Lucía**: Coordinación
- **Tomás**: Miembro
- **Valentina**: Miembro Cumbre
- **Martina**: alta pendiente (menor de edad)

"Reiniciar datos de prueba" vuelve todo al estado inicial.

## Qué está simulado

- La lectura automática de comprobantes devuelve valores de ejemplo.
- El archivo .ics y la exportación CSV se copian al portapapeles.
- Los permisos por rol se aplican solo en la interfaz. En la app real se aplican en la base de datos.
- El alias para transferir, los colores provisorios del logo y los datos de los miembros son de ejemplo.
