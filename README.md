VetConnect — Actividad Semana 2

Respuestas a las preguntas de la actividad
-----------------------------------------
1) ¿Qué diferencia existe entre descargar un ZIP y utilizar git clone?
   - Descargar un ZIP trae solo los archivos en ese momento, sin el historial ni la configuración de Git. git clone crea una copia completa del repositorio incluyendo la carpeta .git, por lo que conserva todo el historial de commits, ramas y la relación con el remoto.

2) ¿Cuándo utilizarías git clone y cuándo git pull?
   - git clone: la primera vez que se obtiene el proyecto en un computador. Se usa para crear la copia completa con historial.
   - git pull: cuando ya tienes el repositorio local y deseas actualizarlo con los cambios nuevos del remoto.

3) ¿Qué comando permite enviar sus commits a GitHub?
   - git push

4) ¿Qué comando permite comprobar si existen modificaciones locales?
   - git status

5) ¿Por qué el segundo computador puede mostrar los commits realizados en el primero?
   - Porque git clone recupera todo el historial de commits desde el remoto, por lo que la copia nueva contiene todos los commits previos.

6) ¿Qué podría ocurrir si comienzas a trabajar desde el segundo computador sin ejecutar git pull cuando ya existe el repositorio?
   - Pueden producirse conflictos al hacer push si el remoto tiene commits que no están en la copia local. El push puede ser rechazado y será necesario hacer git pull para traer y reconciliar los cambios. También puede provocar duplicación de trabajo o pérdida de cambios si no se maneja correctamente.

Evidencia de la actividad
-------------------------
- Repositorio en GitHub: https://github.com/crisito27/VetConnect
- Commits relevantes (ejemplo, visibles en el historial del repo):
  - 9d44e0c — Agrega horario de atención
  - 03b0b94 — Finaliza primer bloque Semana 2 (empty)
  - 4ac35e0 — Integra página de contacto
  - 68e791b — Agrega página de contacto (rama feature/contacto)
  - fb2716a — Agrega sección acerca del sistema
  - f433694 — Agrega listado de servicios
  - 17ef893 — Crea página principal

Rutas locales utilizadas
------------------------
- Copia original del proyecto (laboratorio): C:\Users\AMD Ryzen\VetConnect
- Carpeta que simula el segundo computador: C:\Semana2-PC-Casa\VetConnect

