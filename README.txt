APLICACIÓN MÓVIL DE PARTES DE TRABAJO

EDICIÓN IURDANA
- Repositorio independiente para la cuenta GitHub goikola.
- Usuario administrador: iurdana.
- Las listas y los partes se guardan en cada dispositivo.

Contenido
- Aplicación web instalable (PWA) para Android.
- Funciona sin conexión después de instalarse.
- Guarda los partes en el propio teléfono.
- Exporta siempre los registros en un archivo Excel real (.xlsx).
- Cada parte incluye una tarea: Varios, Eroski, STEF, Barroso, Integra, Recogidas u Otros.
- Al elegir Varios se pueden añadir varias líneas, cada una con matrícula, tarea, horario y kilómetros.
- Incluye 96 trabajadores y 71 matrículas tomados de Listado Erdella.xlsx.
- Solicita usuario y contraseña una sola vez por dispositivo.
- Incluye una pestaña de administración protegida para gestionar trabajadores y camiones.
- Las listas de Administración se guardan en el dispositivo donde se modifican.

INSTALACIÓN EN ANDROID
1. Publique todos los archivos de esta carpeta en una dirección HTTPS.
   La opción más sencilla es GitHub Pages.
2. Abra esa dirección con Google Chrome en el móvil.
3. Pulse "Instalar" en la cabecera. Si no aparece, use el menú de Chrome
   (tres puntos) > "Añadir a pantalla de inicio" o "Instalar aplicación".
4. La aplicación quedará como un icono normal y funcionará sin conexión.

IMPORTANTE
- Los partes de trabajo se almacenan únicamente en el navegador del teléfono.
- Los trabajadores y camiones se pueden personalizar desde Administración en cada dispositivo.
- Antes de borrar datos de Chrome o cambiar de móvil, use "Exportar a Excel".

PRUEBA EN UN ORDENADOR
No abra index.html directamente. Sirva la carpeta con un servidor local HTTPS
o con una plataforma de publicación web. Los service workers no funcionan
desde direcciones file://.
