## Página estática  a git Page 



---
###  paso a paso

1. crear ``index.html`` en el IDE

2. luego abrir un nuevo terminal

3. usar comando: ``node --version``   

4. usar comando: ``npm init -y ``  "para crear en **package.json**"

5. "copiar y pegar el modulo de "gh-pages-npm" ``npm i gh-pages``  

6. crear el archivo ``.gitignore`` en el IDE y en él colocar el ``node_module`` recien creado

7. luego  ``git init``  --> **inicializo repo**
```
git status
git add .
git commit -m "expresion..."
```

8. crear repositorio nuevo en github lo "llamo como quiero"
**mirar el branch en el que estoy** desde el editor o con comando ``git branch``

9. copiar y pegar el comando del repositorio recien creado ej: git remote add origin https://github.com/leonpurple/coinbasecopy.git

10. luego :  git push -u origin main o master segun en que rama este.
*hasta aqui subio el codigo al repositorio pero no aun al git page *

11. ahora ejecuto el comando: ``npx gh-pages -d .`` en 
la consola luego de procesar la info debe dar una respuesta de "published""

12. voy a github 
a la rama master o main 
desplego, allí veré una nueva rama creada **gh-pages** voy  a **settings**
y luego **pages**
pages me da un direccion que me muestar mi sitio 

---
## plantillas staticas para blogs recomendados :

 [gohugo.io](https://gohugo.io/)

 [gatsbyjs.com](https://www.gatsbyjs.com/starters/gatsbyjs/gatsby-starter-wordpress-homepage/)

 [jekillrb.com](https://jekyllrb.com/docs/themes/)