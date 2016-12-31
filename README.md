# Teora de Computación (Tarea 3)
Este repositorio es sólo para facilitar la revisión de la tarea 3, a las personas que quieran revisarla. Podrán encontrar los archivos .xml que utilicé para revisar la tarea 3. En resumen:

*test1.xml*: Este es un xml correcto, y su parser debiese mostrar un mensaje como *"documento correcto"*.

*test2.xml*: Este documento tiene un tag sin cerrar, en este caso especfico el tag de la línea 22 se encuentra sin cerrar. El parser debiese mostrar un mensaje como *error en línea 22, tag sin cerrar o se esperaba >*.

*test3.xml*: Este documento tiene un error en el cierre del tag de la versión de xml. El parser debiese mostrar un mensaje acorde a esta situación.

*test4.xml*: En la línea 118, el tag descripción no está cerrado con /. El parser debiese mostrar un mensaje acorde a esta situación.

Para más detalles, utilizar algún validador XML para verificar todo, por ejemplo: https://www.xmlvalidation.com/
