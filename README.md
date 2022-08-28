## Página estática  a git Page 



---
###  Paso a paso

1. Crear ``index.html`` en el IDE

2. Luego abrir un nuevo terminal ( ctrl+ñ )

3. Utilizar comando: ``node --version``   

4. Utilizar comando: ``npm init -y ``  "para crear en **package.json**"

5. "Copiar y pegar el módulo ``npm i gh-pages``  [traer comando npmjs.com](https://www.npmjs.com/package/gh-pages)

6. Crea el archivo ``.gitignore`` en el IDE y en él coloca el ``node_module`` recien creado

7. Luego  ``git init``   **inicializo repo**
```
git status
git add .
git commit -m "expresion..."
```

8. Crea nuevo repositorio en GitHub lo "llamo como quiero"
**mirar el branch en el que te encuentras** desde el editor o con comando ``git branch``

9. Copiar y pegar el comando del repositorio recien creado ej: git remote add origin https://github.com/leonpurple/coinbasecopy.git

10. Luego : `` git push -u origin main`` o ``master`` segun en que rama este.
*hasta aqui subio el codigo al repositorio pero no aun al git page *

11. Ahora ejecuto el comando: ``npx gh-pages -d .`` en 
la consola luego de procesar la info debe dar una respuesta de *"published"*

12. Ve a GitHub 
a la rama **master** o **main**
desplega, allí verás una nueva rama creada **gh-pages** voy  a **settings**
y luego **pages**
**pages** me da un direccion que me muestra mi sitio 

*puede tardar unos minutos en mostrar los cambios* 

---
## Plantillas estáticas para blogs recomendados :

 [gohugo.io](https://gohugo.io/)

 [gatsbyjs.com](https://www.gatsbyjs.com/starters/gatsbyjs/gatsby-starter-wordpress-homepage/)

 [jekillrb.com](https://jekyllrb.com/docs/themes/)

---


