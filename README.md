# Tarea-Conflictos-Git
Dedicatoria a edson por que me ayudo 
Como primer paso fue crear un nuevo repositorio llamado "Tarea-Conflictos-Git".
Despues de esto se va a clonar para abrir en vs
Seguido de eso se hizo una carpeta llamada git donde se creo el archivo.txt
Despues de eso en vs se creo la rama llamada rama-feature
Despues de haber agregado linea de texto en el archivo se comitean los cambios de la rama feature , con el comando git commit -m "first commit" o en cualquier caso otro nombre en las comillas
Cuando se haya hecho el commit regresamos a main y modificamos el archivo y al igual que la pasada se commitean los cambios con git commit -m "second commit" para cargarlo usar git push
Para fusionar los archivos se usa el comando git merge y el nombre de la rama , siempre tener en cuenta de estar guardando y hacer los commits
Luego de esto se genera un conflicto el cual vs te indica , lo que vas a tener que realizar es elegir de entre 3 opciones , si quedarte con el primero o aceptar el nuevo que viene , en este caso nos quedaremos con el 
que ya teniamos y commitear el cambio en este caso seria git checkout (ours), tambien se va a usar el theirs y la modificacion manual , en el caso de los anteriores tambien dara conflicto pero como primero seleccionamos ours en esta ocacion sera theirs
y al igual que el otro dara conflicto y de igual manera se haran los commits , al final de todo se hara una nueva rama donde se va a fusionar todo que seria git branch rama-resolucion.
