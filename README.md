# CVDS LAB01
Ciclos de Vida del Desarrollo de Software **Laboratorio 1 - Introducción GIT - 2020-2**

## Enunciado 

### Parte I. - Creando repositorios

1. En cada pareja, crear una cuenta en [GitHub](https://github.com/). En una de las dos cuentas, cree un nuevo repositorio. Invite al usuario de la otra pareja como colaborador de dicho proyecto.

2. (Pareja 1) Cree un directorio con los siguientes archivos:

   * libro.txt
    ```
   ----------------------- libro.txt -----------------------
   EL LIBRO MAS FAMOSO DEL MUNDO

   AUTORES:
   CAPITULO UNO
   CAPITULO DOS
   CAPITULO TRES
   ---------------------------------------------------------
    ```

   * feerratas.txt

   ```
   ----------------------- feerratas.txt -------------------
   FE DE ERRATAS


   * El tErmino de la pagima (por lo general) 15 es impreSiso.
   ---------------------------------------------------------
   ```
Cree un repositorio local nuevo utilizando la documentación en [documentación git](https://git-scm.com/docs/git-init)

3. (Pareja 1) Haga **‘push’** del proyecto recién clonado al nuevo repositorio.
    ```
    git push URL_REPOSITORIO master

    ```
4. (Pareja 1) Agregue al libro, como autores, los integrantes de la pareja (sólo el primer nombre). Agregue los cambios para el siguiente commit, haga commit, y haga **‘push’** de dichos commits:
   ```
   git add .
   git commit -m "AUTORES DE LA PAREJA 1 AGREGADOS"
   git push URL_REPOSITORIO master
   ```
5. (Parejas 1 y 2) Revisen a través del cliente Web de GitHub, que el documento haya sido actualizado.
6. (Pareja 2) Clone el proyecto actualizado:
   ```
   git clone URL_REPOSITORIO
   ```
7. (Pareja 2) Agregue los autores de su Pareja al libro (sólo el primer nombre). Agregue los cambios para el siguiente commit, haga commit, y haga ‘push’ de dichos commits:
   ```
   git add .
   git commit -m "AUTORES DE LA PAREJA DOS AGREGADO"
   git push URL_REPOSITORIO master
   ```
8. (Pareja 1) Obtenga los ‘commits’ realizados por la pareja anterior, y revise que los mismos hayan sido aplicados al documento
   ```
   git pull URL_REPOSITORIO master
   ```
9. Utilice en comando **gitk** para verificar el historial de cambios sobre el repositorio.


10. (Parejas 1 y 2 al tiempo)
   *   Pareja 1: Remueva el paréntesis de la línea 5 de la fe de erratas.
   *   Pareja 2: Arregle los errores de ortografía en el archivo fe de erratas.
   *   Pareja 1 y 2: Agreguen los cambios a sus repositorios locales, hagan commit y push. ¿Las dos parejas lo pudieron hacer?, ¿Qué quedó al final en la versión oficial?

Si para alguno no es posible hacer el ‘push’ (por consistencia), haga antes un pull a la rama ‘master’ del repositorio en GitHub con ‘rebase’:
```
git pull --rebase URL_REPOSITORIO master
```

### Parte II. - Introducción General GIT
1. Revise la documentación de Git: <https://git-scm.com/doc>
2. Revise la página web <http://ndpsoftware.com/git-cheatsheet.html> para entender la diferencia entre las partes de GIT y los comandos disponibles para cada una.
3. Investigue un poco acerca de Markdown y de cómo realizar un archivo README.
4. Realice el tutorial de Markdown disponible en: <https://commonmark.org/help/tutorial/>
5. En el repositorio de la Parte I, cree una carpeta con su nombre.
6. Cree un archivo Readme en formato Markdown en su carpeta donde incluya su nombre, datos básicos, plan de estudios, etc. Agregue cualquier información que desee mostrar acerca de usted.
7. El archivo debe incluir al menos 1 de cada uno de los siguientes elementos (negrita, cursiva, títulos, subtítulos, párrafos, listas ordenadas y no ordenadas, enlaces, imágenes y fragmentos de código).


### Parte III. - GIT Branching
1. Ingrese a la página web: [GitBraching](https://learngitbranching.js.org/)
2. desarrolle los ejercicios


