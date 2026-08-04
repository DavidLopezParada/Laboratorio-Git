
# Laboratorio Git

En este laboratorio he practicado los comandos básicos de Git: crear un repositorio, conectarlo con GitHub, hacer commits, trabajar con ramas y hacer un merge.

---

## 1. Crear el repositorio en local

Creé una carpeta para el proyecto y dentro inicialicé el repositorio con `git init`.

## 2. Subir el repositorio a GitHub

Creé un repositorio nuevo en GitHub y lo conecté con mi repositorio local usando `git remote add origin <url>`. Y verifiqué que la conexión se hubiera establecido correctamente con `git remote -v`.

## 3. Hacer un commit y un push

Creé un archivo `prueba.js` y escribí un `console.log`. Lo añadí al staging con `git add`, hice un commit con un mensaje descriptivo y subí los cambios a GitHub con `git push`.

## 4. Crear una rama

Creé una nueva rama llamada `development` y cambié a ella. Modifiqué el mensaje del `console.log` de `prueba.js`, hice commit de los cambios en esa rama y los subí a GitHub.

## 5. Hacer un merge

Volví a la rama principal y fusioné `development` con un `git merge`. Como ambas ramas habían modificado la misma línea del archivo, tuve que resolver un conflicto combinando el contenido de las dos versiones. Y finalmente subí los cambios finales con `git push`.