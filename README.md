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

