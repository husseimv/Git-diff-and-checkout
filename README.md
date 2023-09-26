**

## Pasos para utilizar Git Diff (ver video en la parte superior Git Diff.mp4)

 1. Una vez ya creado el repositorio (Git init), sus respectivos archivos (touch) y luego de haberle hecho cambios seguir con el paso 2.
 2. Git add . (Agregando los archivos creados en el paso 1).
 3. Git commit -m "..." (Entre comillas escribir el mensaje relacionado al commit).
 4. Git diff (La consola mostrará la diferencia del archivo nuevo al original).
	 4.1. Con un signo "+" y en verde: mostrará las lineas de código que han sido agregadas.
	 4.2. Con un signo "-" y en rojo: mostrará las lineas de código que han eliminadas.


## Pasos para utilizar Git Checkout (ver video en la parte superior Git Checkout.mp4)

1. Este proceso se hace útil cuando se ha hecho más de un commit al repositorio.
2. Una vez ya creado el repositorio (Git init), sus respectivos archivos (touch) y luego de haberle hecho cambios seguir con el paso 2.
3. Git log --oneline (Este comando muestra una ruta de cada uno de los commits mediante una especie de serial que se conforma con números y letras en donde HEAD señala la última versión).
4. Git checkout "..." (Entre comillas se colocará la ruta deseada obtenida en el paso anterior y así se podrá visualizar el estado de esa ruta).
5. Git checkout master (Este comando mostrará la última version existente en el repo).

6. Hola Lucianny <b> Vergara </b>
