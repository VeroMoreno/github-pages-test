# GitHub Pages 

## Probando veroMoreno.github.io 🚀

De momento subiendo una pequeña prueba para ver como funciona

## Problemas 🔧

**1. Error en la terminal**
```
git push -u origin master
error: src refspec veroMoreno.github.io does not match any
```

**Solución:**
Primero comprobé en la terminal dónde estaba referenciando: git show-ref
```
show-ref
```
La respuesta fue refs/remotes/origin/main

Por defecto Github pages publica en máster y en mi caso mi rama principal es main.
Para modificarla tuve que accedera Settings del proyecto y en la parte de GitHub Pages modificar el source: Branch: main 


**1. He hecho push pero no me carga la página**

gitHub pages no publicará si no le asignas un template. Tuve que elegir un "**Jekyll theme**" por defecto.

seguimos