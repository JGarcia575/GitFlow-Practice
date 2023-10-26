### GitFlow
-----------------------
## Comandos Git
-------------------
* Crear un repositorio con el comando git init.
* Agregar los cambios al staging area con el comando git add o git add . 
* Luego hacer commit de los cambios con el comando git commit -m "descripción del commit".
* Crear un repositorio remoto en Git Hub.
* Agregar los siguiente comandos para subir nuestro código al repositorio remoto:
    - git remote add origin https://github.com/JGarcia575/GitFlow-Practice.git.
    - git branch -M main.
    - git push -u origin main.
* Crear una rama con el comando git checkout -b develop.
* Apretar en subir cambios para que la rama develop también se suba al repositorio remoto. 
* O utilizar el comando git push -u origin develop (el nombre de la rama).
* Crear la rama feature, porque según Gitflow una rama por cada funcionalidad, con el comando
git checkout -b  feature/say-hello.
* Subir la rama feature/say-hello.
* Luego ejecutar los comandos: 
    - git add .
    - git commit -m "feat: se ha agregado la función  sayHello". Esto es una buena práctica.  

* Ya con la rama feature en el repositorio remoto, podemos seguir añadiendo cambios a esa rama con los comandos:
    - git add .
    - git commit -m "feat: se ha añadido más contenido al mensaje".
    - git push.
* Fusionar la rama feature/say-hello con la rama develop con el comando git merge --no-ff.
* Luego crear otra rama feature/say-bye con el comando git checkout -b  feature/say-bye.
* Subir la rama al repositorio remoto y luego:
    - git add . 
    - git commit -m "feat: añadida la funcionalidad say-bye".
    - git push.
* Crear la rama release/1.0.0:
    - el primer numero ---> cambios muy grandes, rompe con al compatibilidad entre versiones.
    - el segundo numero ---> minor, nuevas funcionalidades, no rompe la compatibilidad con lo que se ha creado antes.
    - hotflix --> cambios rápidos.
* Para agregar una tag git tag -a -m "versión 1.0.0 lista"
* Luego subir la etiqueta.
* Crear la rama hotfix a partir de la rama main con el comando git checkout -b hotfix.
* Hacer la modificación. En este caso cambiar la función say-bye.