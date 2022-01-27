#codigo 13 

## comandos para  GIT

```
git init
```
-Este comando solo see hace una ves por proyecto, sirve para inicializar nuestro proyecto con git
- :eye: crea una carpeta oculta en .git

git status
```
-Poder listar  y ver los archivos estan listos para  subir
-Ojo en caso los archivos no esten listos se veran de color rojo  y cuando lo este seran de color verde

```
git add .
git add nombre_de_archivo
```
-Se encarga de agregar los archivos a la memoria de GIT es decir los guarda en un stash

```
git commit -m "comentario"
```
-Crea un punto en la linea de tiempo de nuestros cambios y a estos se les posible adjuntar un comentario
- :eye: Los comentarios deben de  estar relacionados a los cambios que hice, esto es una recomendacion

```
git push origin main
```
-Sirve para poder  subir los cambios a nuetro repositorio en la nube, en este caso github
 


```
git pull origin main
```
-Se encarga de descargar los cambios de nuestro repositorio en la nube  en  este caso github

```
git clone
```
- descarga toda la carpeta desde github
 
```
git branch
```
- este comando sirve para poder listar los brach que teng localmen ten y me dice en cual me encuestro actulamente 

```
git checkout -b nombre del branch
```

- sirve para  poder moverse entre branchs
- si el checkout no tiene el -b solo es para moverse entre branch

``` 
git merge


```
git fetch
```
- Actualiza cambios en la rama pero referente a nuevas ramas creadas

git branch -d  -d elimina 