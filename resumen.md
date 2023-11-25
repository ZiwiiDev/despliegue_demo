## Resumen de comandos git - Oliver Fabian Stetcu

|Comando|Función|Ejemplo
|-|-|-|
|init|Inicia un repositorio|git init
|config|Configura opciones de Git|git config --global user.name "nombre"
|add|Añade los cambios al staged|git add archivo.txt
|commit|Guarda los cambios en el repositorio|git commit -m "mensaje"
|status|Muestra el estado de los archivos en el repositorio|git status
|log|Muestra el historial de commit|git log
|diff|Muestra las diferencias entre commits, ramas, archivos...|git diff archivo.txt
|show|Muestra información de un commit|git show -commit-
|tag|Administra tags (etiquetas)|git tag -a v1.0 -m "Versión 1.0"
|restore|Restaura archivos en el directorio de trabajo|git restore archivo.txt
|revert|Crea un commit que deshace todo lo que se ha hecho|git revert --no-edit HEAD
|reset|Reestablece a la versión antes del commit|git reset --mixed HEAD^
|branch|Permite crear, listar o eliminar ramas|git branch nueva-rama
|switch|Cambia de rama|git switch nueva-rama
|merge|Fusiona ramas|git merge otra-rama
|remote|Administra repositorios remotos|git remote add origin -URL-
|clone|Clona un repositorio remoto|git clone -URL-
|push|Sube los cambios al repositorio remoto|git push origin master
|pull|Descarga cambios del repositorio remoto|git pull origin master
|fetch|Descarga cambios del repositorio remoto (sin fusionar)|git fetch origin
