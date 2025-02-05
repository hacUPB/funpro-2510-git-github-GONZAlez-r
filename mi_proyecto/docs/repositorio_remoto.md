Inicia sesión en GitHub en https://github.com/
 Crea un nuevo repositorio haciendo clic en el botón "New" o accediendo a https://github.com/new.

 Configura el repositorio:
Escribe un nombre para el repositorio (por ejemplo, mi_proyecto).

Opcionalmente, agrega una descripción.

Elige si será público o privado.

NO marques la opción de inicializar con README.md, .gitignore o licencia.

 Haz clic en "Create repository".

Copia la URL del repositorio, que tendrá un formato como:

https://github.com/usuario/mi_proyecto.git
2. Configurar el repositorio local
Si ya tienes un proyecto local, accede a la carpeta donde está ubicado
ejemplo
cd ~/funpro-2510-git-github-GONZAlez-r/mi_proyecto
Verifica el estado del repositorio:
git status
Si tienes archivos que deseas rastrear, agrégales un commit
git add .
git commit -m "Primer commit: estructura inicial"

 3. Vincular el repositorio local con GitHub

git remote add origin https://github.com/usuario/mi_proyecto.git
Verifica que se haya agregado correctamente con:

git remote -v
Debería mostrar algo como:
origin  https://github.com/usuario/mi_proyecto.git (fetch)
origin  https://github.com/usuario/mi_proyecto.git (push)

 4. Subir el repositorio local a GitHub
Si tu rama principal se llama main (verifícalo con git branch), usa:
git branch -M main
git push -u origin main
Si GitHub te solicita autenticación, inicia sesión en GitHub
5. Verificar que el código está en GitHub
•	Ve a tu repositorio en GitHub y recarga la página.
•	Deberías ver los archivos subidos.
6. Sincronizar cambios futuros
Cada vez que hagas cambios en tu código y quieras subirlos a GitHub, usa:
git add .
git commit -m "Descripción del cambio"
git push origin main


