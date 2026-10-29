# Torneo de Truco

Aplicación web de una sola página para organizar un torneo de truco con eliminación directa. Permite cargar participantes, formar equipos, sortear cruces, registrar resultados y exportar la información.

## Cómo abrirla

1. Descargá o cloná este repositorio.
2. Abrí `TrucoTournament.html` en un navegador moderno.
3. No hace falta instalar dependencias ni ejecutar un servidor: la aplicación está contenida en ese archivo.

## Cómo organizar un torneo

1. En **Participantes**, agregá los nombres uno por uno o importá un CSV con un nombre por fila (se toma la primera columna).
2. En **Equipos**, elegí la modalidad de 1, 2 o 3 jugadores por equipo. Podés armar los equipos de forma aleatoria o manual.
3. En **Cuadro**, generá el sorteo para iniciar la eliminación directa. Si corresponde, el cuadro asigna pases libres cuando la cantidad de equipos no completa una llave de potencias de dos.
4. En **Resultados**, revisá el historial y la clasificación. Desde cada partida pendiente podés cargar al ganador; también es posible editar o deshacer un resultado.

## Datos y exportaciones

- Los cambios se guardan automáticamente en el almacenamiento local del navegador que estés usando. No hay una cuenta, base de datos ni sincronización entre dispositivos.
- Usá **Copia de seguridad** para descargar un archivo JSON y **Importar** para restaurarlo. Guardá una copia antes de cambiar de navegador o dispositivo; importar reemplaza el torneo abierto.
- También podés exportar participantes y resultados como CSV, descargar una copia HTML de la aplicación con el estado actual, o imprimir/guardar el cuadro como PDF.

> Si borrás los datos del sitio en el navegador, también podés perder el torneo. Conservá el archivo JSON de respaldo.
