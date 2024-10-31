# portafolio de Alejandro Ledezma
Mi información de contacto, habilidades y proyectos realizados
Clase de agregar y cambiar
Clase para clonar y subir al repositorio

##Pasos para clonar y desplegar mi portafolio

#### **Paso 1: Clonar el Repositorio desde GitHub a tu Máquina Local**

##### 1. Acceder a GitHub:
• Abre tu navegador web y ve a GitHub.
• Inicia sesión con tu cuenta.

##### 2. Seleccionar el Repositorio:
• Navega a la página del repositorio de tu portafolio. Si aún no tienes uno, necesitarás crear un nuevo repositorio.

##### 3. Copiar la URL del Repositorio:
• En la página del repositorio, busca el botón verde que dice "Code".
• Haz clic en él y copia la URL que aparece. Puedes elegir entre HTTPS o SSH, pero HTTPS es más común para principiantes.

##### 4. Abrir la Terminal o Línea de Comandos:
• En tu computadora, abre windows y la opcion de nueva terminal.

##### 5. Clonar el Repositorio:
• Navega al directorio donde deseas clonar el repositorio usando el comando cd. Por ejemplo:
     cd /ruta/a/tu/directorio
• Clona el repositorio usando el comando git clone seguido de la URL que copiaste:
     git clone https://github.com/tu-usuario/nombre-del-repositorio.git

####  **Paso 2: Realizar Cambios en tu Portafolio Localmente**
##### 1. Navegar al Directorio del Repositorio Clonado:
• Usa el comando cd para entrar en el directorio del repositorio clonado:
     cd nombre-del-repositorio
##### 2. Editar Archivos:
• Abre los archivos de tu portafolio en tu editor de texto o IDE preferido (como Visual Studio Code, Sublime Text, etc.).
• Realiza los cambios o actualizaciones que desees en tu portafolio.
#### Paso 3: Confirmar y Enviar los Cambios a GitHub
##### 1. Agregar los Cambios:
• Asegúrate de estar en el directorio del repositorio y ejecuta el siguiente comando para agregar todos los cambios:
     git add .
##### 2. Confirmar los Cambios:
• Crea un commit con un mensaje que describa los cambios realizados:
     git commit -m "Descripción de los cambios realizados"
##### 3. Enviar los Cambios a GitHub:
• Sube los cambios al repositorio remoto en GitHub:
     git push origin main
• Asegúrate de reemplazar main con el nombre de la rama que estás usando si es diferente.
#### Paso 4: Desplegar con GitHub Pages
##### 1. Ir a la Configuración del Repositorio en GitHub:
• En tu repositorio en GitHub, haz clic en la pestaña "Settings" (Configuración).
##### 2. Habilitar GitHub Pages:
• Desplázate hacia abajo hasta la sección "Pages".
• En "Source" (Fuente), selecciona la rama que deseas usar para GitHub Pages (generalmente main o master).
• Si es necesario, selecciona la carpeta raíz o /docs como la fuente de contenido.
• Haz clic en "Save" (Guardar).
##### 3. Verificar el Despliegue:
• GitHub Pages generará una URL para tu sitio. Esta URL aparecerá en la misma sección de "Pages".
• Visita la URL para asegurarte de que tu portafolio se ha desplegado correctamente.
