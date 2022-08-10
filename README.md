# Proyecto-Logica-2021
Proyecto realizado en la materia Lógica para Ciencias de la computación.
Nonograma en React + Prolog

Para correr el proyecto

Setup y ejecución del servidor Pengines
Descargar e instalar el SWI-Prolog.

Levantar el servidor ejecutando en SWI-Prolog el run.pl en la carpeta pengines_server:

cd pengines_server
swipl run.pl

o haciendo doble click sobre el run.pl.

La primera vez que se ejecute el run.pl se pedirá definir un username y un password para acceder a la consola web admin del servidor, elegir cualquiera (por ejemplo, username: 'lcc' y password: 'lccdcic'), pero no dejar vacíos.

El servidor escuchará en http://localhost:3030

Ir a http://localhost:3030/admin/server.html para ver la consola web admin.

La carpeta pengines-master/apps/proylcc contiene el código prolog del tic tac toe. Cada vez que se modifica este código es necesario bajar y volver a levantar el servidor para que se reflejen los cambios.

Setup y ejecución de la aplicación React
Descargar una versión reciente de Node.js.

Ejecutar

npm install

en el directorio del proyecto (tic-tac-toe) para instalar las dependencias (librerías) localmente, en la carpeta node_modules.

Ejecutar

npm start

en el directorio del proyecto para correr la app en modo desarrollo.

Abrir http://localhost:3000 para ver la aplicación en el browser.

La página se refresca automáticamente cuando cambia el código.