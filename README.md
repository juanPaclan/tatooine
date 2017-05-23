# <center>  __ _tatooine_ __ </center>

>local: se refiere al estado de manera local, en la computaro donde se encuentra el archivo individual.

>remote: rastrea y en lista los repositorios de manera remota, los archivos en el servicio wed.

>init: crea un espacio para reinicializar los repositorios existentes.

>clone: clona un repositorio en el servidor wed y lo ingresa en un nuevo repositorio local.

>add: Agrega los archivo en el cotenedor index.

>commit: registra los cambios en los repositorios.

>push: Actualizacion remota de la asociacion de los objetos en el servicio wed.

>pull: trae la integracion dentro de los repositorios locales.

>*merge: Integra dos o mas en el historial reunido en el desarrollo.*

<big> __Las fasse de git son:__

-  __UNTRACKED:__  son los archivo unicos sin modificacion alguna.

-  __STAGED:__  se agrega el archivo.

-  __TRACKED:__  se monitoreta el archivo y se detecta si se realizan cambios.

-  __COMMITTED:__  se registran los cambios en la linea de tiempo en el servicio web.

-  __MODIFIED:__  en esta etapa se  modifican los archivos y se mantienen de forma local asta que se realize un commit para subir la información en el servicio web.

****                  Como funciona GIT

Existen dos formas de trabajo en git una es de forma local y otra en grupo, cuando se trabaja de forma local los repositorios se suben a git para crear una linea de tiempo, si se trabaja en grupo los repositorios se tienen que descargar de git.

Nota: todos los movimientos se realizan desde la terminal y en linea de comandos.

![Fases de Comunicación](https://camo.githubusercontent.com/6d599db858665e9813a8103f356678c8c5e4e3e4/687474703a2f2f6934332e74696e797069632e636f6d2f32726d773769782e706e67 "Fases de Comunicación")

- Initalize:en esta etapa se sube el repositorios o se clona el repositorios desde la plataforma.
- Update:si se realizan modificaciones en algún archivo se tiene que realizar la actualización donde se tiene que utilizar el comando git pull para actualizar los repositorios o "git ftch" para descargar las actualizaciones realizadas por otras personas.
- Changes: en esta etapa se registran los cambios donde se utilizan los comandos "git commit -a" para agregar el mensaje de la modificación, el comando "git add nombre-de-archivo" este comando agrega solo el archivo modificado posteriormente se realiza el "git-commit-Nombre" y por ultimo "git push origini nombre-de-la-rama" para la Actualización de la rama de trabajo.
- Revert: en esta etapa su puede revertir los cambios dealizados en la rama.
- Diff: en esta etapa se puede mostra las diferencias realizadas.



<big> __Las cosas que no se debe de realizar en GIT son:__



1.- las modificaciones de los archivos no se pueden realizar en el master.

2.- cuando se agregan archivos al servicio web asegurarse que se encuentren en la rama de desarrollo y no en el master, siempre se debe de identificar donde se trabaja.

3.- cuando se realize un pull no aserlo directamente en el master asta que este todo verificado.
