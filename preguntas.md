1. ¿Qué diferencia hay entre confirmar (commit) y subir (push)?   
   Confirmar guarda los cambios en tu historial local y subir envía esos commits desde tu ordenador a GitHub

2. ¿Qué significan 1↑ y 1↓ en la barra de estado de VS Code?   
   1↑ indica un commit local pendiente de subir a GitHub y 1↓ indica un commit en GitHub pendiente de extraer a tu copia local.

3. ¿Por qué en esta práctica usaste un repositorio privado un correo noreply?
   Se usa un repositorio privado porque los commits previos de la Práctica 0 conservan tu correo real y no es accesible públicamente hasta invitar al docente, y un correo noreply para ocultar tu dirección personal en los commits futuros.

4. ¿Por qué la copia clonada no mostraba un cambio hecho en GitHub hasta que sincronizaste?
   Porque cada copia local es independiente y solo recibe los commits nuevos de GitHub cuando sincronizas para traerlos a tu equipo.

5. ¿Qué hace la palabra Closes seguida de un número en la descripción de una Pull Request?
   Enlaza la Pull Request con el Issue de ese número y cierra automáticamente el Issue cuando se fusiona la Pull Request.
   
6. ¿Por qué es mejor trabajar en una rama y fusionarla mediante Pull Request que editar main
directamente?
    Porque aisla tu trabajo en una rama mientras se desarrolla, permite revisarlo (en equipo otras personas pueden aprobarlo) y enlaza la tarea con la Pull Request antes de integrarla en main de forma ordenada.