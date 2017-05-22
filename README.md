# tatooine
local: se refiere al estado de manera local, en la computaro donde se encuentra el archivo individual.
remote: rastrea y en lista los repositorios de manera remota, los archivos en el servicio wed.
init: crea un espacio para reinicializar los repositorios existentes.
clone: clona un repositorio en el servidor wed y lo ingresa en un nuevo repositorio local.
add: Agrega los archivo en el cotenedor index.
commit: registra los cambios en los repositorios.
push: Actualizacion remota de la asociacion de los objetos en el servicio wed.
pull: trae la integracion dentro de los repositorios locales.
 merge: Integra dos o mas en el historial reunido en el desarrollo.
Las fasse de git son:
UNTRACKED: son los archivo unicos sin modificacion alguna.
STAGED: se agrega el archivo.
TRACKED: se monitoreta el archivo y se detecta si se realizan cambios.
COMMITTED: se registran los cambios en la linea de tiempo en el servicio web.
MODIFIED: en esta etapa se  modifican los archivos y se mantienen de forma local asta que se realise un commit para subir la informacion en el servicio web.
Las cosas que no se debe de realizar en GIT son:
1.- las modificaciones de los archivos no se pueden realizar en el master.
2.- cuando se agregan archivos al servicio web asegurarse que se encuentren en la rama de desarrollo y no en el master, siempre se debe de identificar donde se trabaja.
3.- cuando se realize un pull no aserlo directamente en el master asta que este todo verificado.
