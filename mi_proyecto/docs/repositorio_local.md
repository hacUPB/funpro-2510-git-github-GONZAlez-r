El archivo .gitignore es utilizado por Git para decirle qué archivos o directorios no deben ser rastreados ni versionados. Esto es útil para excluir archivos temporales, de configuración, o de sistemas operativos que no son necesarios en el repositorio.
Ayuda a evitar archivos innecesarios, proteger información sensible y mejorar el rendimiento del repositorio al simplificar su contenido.
1.	 Se crea un repositorio
Con mkdir nombre_repositorio
2.	Crea un archivo .gitignore en el directorio raíz del repositorio:
touch .gitignore
para editar el archivo .gitignore se puede  abrir con un editor de texto como vim .gitignore y agregar las reglas para ignorar archivos o directorios.

3.	Se agrega archivos y ecommits
touch README.md

se puede agregar el archivo al repositorio
git add README.md

git commit -m "Primer commit"

