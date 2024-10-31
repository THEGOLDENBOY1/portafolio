Explanation of Basic Git Commands and Their Purposes
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"
Configura tu nombre de usuario y correo electrónico, que se asocian con tus commits. Esto es importante para identificar quién hizo qué cambios en un proyecto.
git clone https://github.com/usuario/repositorio.git
Crea una copia local de un repositorio remoto. Esto te permite trabajar en el proyecto en tu máquina local.
git status
Muestra el estado actual del repositorio, incluyendo archivos modificados, nuevos archivos no rastreados, y archivos listos para ser confirmados (staged).
git add archivo.txt
git add .
Añade cambios de archivos específicos al área de preparación, preparándolos para ser confirmados en el próximo commit. El segundo comando añade todos los cambios en el directorio actual al área de preparación.
git commit -m "Mensaje del commit"
Guarda los cambios preparados en el historial del repositorio. El mensaje del commit debe describir los cambios realizados.
git push origin main
Envía los commits locales a la rama especificada del repositorio remoto. Esto actualiza el repositorio remoto con tus cambios.
git pull origin main
Descarga y fusiona cambios desde el repositorio remoto a tu rama local. Esto asegura que tu copia local esté actualizada con los últimos cambios del remoto.
git branch nombre-de-la-rama
Crea una nueva rama en el repositorio. Las ramas se utilizan para desarrollar características o corregir errores de forma aislada.
git checkout nombre-de-la-rama
Cambia el directorio de trabajo a la rama especificada. Esto te permite trabajar en diferentes partes del proyecto sin interferir con la rama principal.
git merge nombre-de-la-rama
Fusiona los cambios de la rama especificada con la rama actual. Esto se utiliza para integrar cambios de una rama de desarrollo a la rama principal.
git branch -d nombre-de-la-rama
Elimina una rama que ya no es necesaria. Esto ayuda a mantener el repositorio limpio y organizado.


