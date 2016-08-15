# ManualGit



##¿Qué es Git?


Git es un sistema distribuido de control de versiones libre y de código abierto diseñado para manejar proyectos pequeños hasta grandes con rapidez y eficiencia.



##¿Cómo Instalar Git? 

Podemos Instalar Git en cualquier sistema operativo, solo clikea en tu sistema operativo y sigue la guía de instalación  [Mac OS X][1], [Windows ][2], [Linux][3]
[1]: https://git-scm.com/download/mac
[2]: https://git-scm.com/download/win
[3]: https://git-scm.com/download/linux

##Iniciando con Git 

###Configuración Básica

El primer paso después de haber instalado git en nuestra computadora es abrir la terminal en el caso de MAC OS X y Linux, para el caso particular de Windows tras la instalación solo tenemos que abrir "GitBash".

Para comenzar a utilzar git lo principal es configurar nuestro nombre y correo, para eso solo tenemos que introducir los siguientes comando en nuestra terminal. 

<pre>
git config --global user.name "Donaldo"
git config --global user.email "donaldo.fndz@gmail.com"
</pre>

Una vez que configurado eso, el siguiente paso es entrar a un directorio desde la terminal, a continuación veremos comandos básicos para moverse entre directorios ya sea en la terminal o en "GitBash".

El comando `cd` nos sirve para movernos entre directorios

<pre>
cd DirectorioAlQueEntraremos
cd .. 
</pre>

Dentro de cada directorio existen referencias hacia más directorios y también hacía el directorio padre, el directorio padre lleva el nombre de `..` es por eso que si nosotros utilizamos el comando `cd ..` iremos hacía el directorio padre.






