## ex1
1. Con git init inicializo el repo
2. Creo el fichero dentro de la carpeta, click derecho nuevo archivo
3. Añado el fichero con git add. Se encuentra en la mesa de trabajo (Staging Area)
4. No tengo ningun repositorio remoto apuntando, por lo tanto da error
5. Como he dicho antes no tenemos nigun repo en la nube
6. En github creo un repositorio en la nube y lo asocio con lo siguientes comandos:
   ```bash
    git remote add origin https://github.com/bootjavacris/repo01.git
    git branch -M main
    git push -u origin main
   ```
   7. Ahora aparece porque con git remote hemos añadido el repositorio de github, hemos hecho que apunte ahí.
   8. 