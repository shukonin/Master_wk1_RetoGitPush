# Master_wk1_RetoGitPush

[Reto][Semana1]: crear un repositorio para ubicar los diagramas de flujo solicitados. Los archivos deben ubicarse en el repositorio haciendo 'push' desde la terminal

Secuencia de pasos y comandos usados para hacer el push:

1. Crear el repositorio en GitHub
2. Abrir terminal y ubicarme en directorio donde estan los diagramas
3. Inicializo mi espacio de trabajo:
$ git init

4. Hago tracking a mis archivos:
$ git add .

5. Hago commit para alojarlos en repositorio local:
$ git commit -m "Primer commit de mis diagramas"

6. Reviso status
$ git status

7. Conecto mi repositorio local con el repositorio remoto usando la URL
$ git remote add origin "https://github.com/shukonin/Master_wk1_RetoGitPush.git"

8. Valido la conexion
$ git remote -v

9. Actualizo mi repositorio local forzando un poco debido a warning de unrelated histories
$ git pull origin master --allow-unrelated-histories

10. Reviso que haya traido el README.md y el status
$ ls -al
$ git status

11. Hago push al repositorio remoto
$ git push origin master

12. Valido en GitHub y aparecen los archivos

13. Chequeo local:
$ git log
$ git status

13. Agrego todo este contenido al README en mi repositorio local
$ vim README.md

14. Hago commit para guardar los cambios en el README.md
$ git commit -am "Agrego el paso a paso del proceso para hacer push en GitHub"

15. Hago el push final para que la ultima version del readme quede en GitHub
$ git push origin master
