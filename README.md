# ing-lab-4

## Trabajo Practico N°1

### __1- Descargar Git y eleccion de IDE__

* Descargar e instalar Git
* Elegir IDE como cliente visual. En mi caso elegi VS Code.

### __2- Crear un repositorio local y agregar archivos__

* Creo un repositorio local en un directorio de nuestra pc.

    ![](assets/iniciorepo.png "Creo un repositorio local")

* Agrego un archivo README.md, que contiene mi nombre y un link al archivo CV.md. Este ultimo estara al mismo nivel de carpeta .
    * [README.md](https://github.com/dbobadillabarcelo/TP1-Sistemas-de-control-de-versiones)
    * [Mi CV](https://github.com/dbobadillabarcelo/TP1-Sistemas-de-control-de-versiones/blob/master/CV.md)

    ![](assets/2.png "se agregan archivos y muestro estado")
    ![](assets/3.png "se hace el primer commit")

### __3- Crear un repositorio remoto__

* Creo repositorio en GitHub.

* Asocio el repositorio local con el repositorio de Github y subo lo local al repo.


    ![](assets/4.png "link del repo local al remoto y push del commit")

### __4- Familiarizarse con el concepto de Pull Request__

* Creo un branch local y agrego los cambios a dicho branch
    

     ![](assets/5..png "Creo un branch con el nombre dev")

* [Pull Request](https://github.com/dbobadillabarcelo/TP1-Sistemas-de-control-de-versiones/blob/master/PR.md)

* Subo el cambio a dicho branch y creo un pull request.


    ![](assets/6.png "creamos PR con el agregado del archivo PR.md y tambien una modificacion en el README")


    ![](assets/7.png "Proceso de revision")

* Dentro de GitHub completo el proceso de revisión y mergeo PR a la rama master.

    ![](assets/8.png "volvemos al master")
    ![](assets/9.png "y hacemos el merge de las dos ramas")


### __5- Mergear código con conflictos__

*   Creo un segundo directorio y clonamos el repo de GitHub.
*   En el primer directorio, modifico el CV.md cambiando algunas lineas.
*   Hago commit y subo el cambio a master en GitHub.
*   En el clon hago cambios en las mismas lineas del CV.
*   Intento subir el cambio, haciendo un commit y luego un push. Se genera un conflicto ya que no sabe con cual quedarse.

    ![](assets/10.png "intento pushear a master desde el CLONE que realizamos y ocurre un error ya que hemos cambiado las mismas lineas en los archivos")


*   Resolvemos los conflictos del código eligiendo alguna de las opciones.
   ![](assets/11.png "Vemos el conflicto generado y el ide nos muestra varias opciones para resolverlo")

*   Explicamos el significado de las versiones LOCAL, BASE y REMOTE en el README.
    * [LOCAL, BASE, REMOTO](https://github.com/dbobadillabarcelo/TP1-Sistemas-de-control-de-versiones)      
*   Pusheamos el cambio mergeado.

     ![](assets/12.png "Se resuelve el conflicto y se pushea los cambios")

### __6- Algunos ejercicios online__

*   Entro a la página https://learngitbranching.js.org/
*   Completo los ejercicios de Introduction Sequence

    ![](assets/13.png "resolvemos los ejercicios introductorios")
