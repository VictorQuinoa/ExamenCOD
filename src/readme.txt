Examen COD 2Av.

1.Hacemos un fork con todas las ramas del repositorio y traemos las ramas al local con git fetch.

2.Creamos la rama readme con git branch readme y hacemos git checkout readme para crear el readme.

3.Hacemos checkout en la rama interface y hacemos un reset al commit anterior al que queremos eliminar para asi omitir el último commit.

4.Una vez eliminado el commit, volvemos con checkout a la rama main y hacemos merge de datos e interfaz.

5.Con git tag -a v1.0 creamos la etiqueta de versión.

6.Hacemos push y creamos una release en el repositorio con la etiqueta v1.0.

7.Como el git ignore no esta incluido hago un ammend para solucionarlo.

8.Una vez arreglado hacemos push y lanzamos la release final.

9.Hacemos push a la rama readme como rama independiente.