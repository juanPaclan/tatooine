# <center>  __ _tatooine_ __

local: se refiere al estado de manera local, en la computaro donde se encuentra el archivo individual.

remote: rastrea y en lista los repositorios de manera remota, los archivos en el servicio wed.

init: crea un espacio para reinicializar los repositorios existentes.

clone: clona un repositorio en el servidor wed y lo ingresa en un nuevo repositorio local.

add: Agrega los archivo en el cotenedor index.

commit: registra los cambios en los repositorios.

push: Actualizacion remota de la asociacion de los objetos en el servicio wed.

pull: trae la integracion dentro de los repositorios locales.

 merge: Integra dos o mas en el historial reunido en el desarrollo.

<big> __Las fasse de git son:__

<center>
  - _ __UNTRACKED:__ _ son los archivo unicos sin modificacion alguna.

- _ __STAGED:__ _ se agrega el archivo.

- _ __TRACKED:__ _ se monitoreta el archivo y se detecta si se realizan cambios.

- _ __COMMITTED:__ _ se registran los cambios en la linea de tiempo en el servicio web.

- _ __MODIFIED:__ _ en esta etapa se  modifican los archivos y se mantienen de forma local asta que se realise un commit para subir la informacion en el servicio web.


<big> __Las cosas que no se debe de realizar en GIT son:__

<center>
1.- las modificaciones de los archivos no se pueden realizar en el master.
<center>
2.- cuando se agregan archivos al servicio web asegurarse que se encuentren en la rama de desarrollo y no en el master, siempre se debe de identificar donde se trabaja.
<center>
3.- cuando se realize un pull no aserlo directamente en el master asta que este todo verificado.
