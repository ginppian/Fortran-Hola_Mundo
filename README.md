Fortran - ¡Hola Mundo!
===========

## Descripción:

<p align="justify">
	Es un hola mundo en Fortran 90 en Mac.
</p>


## Técnico:

* macOS Sierra 10.12.5

<p align="justify">
	Si eres desarrollador seguramente ya tendrás instalado <i>Xcode</i> y las herramientas necesarias para compilar desde linea de comandos, las cuales incluyen una <b>adaptación</b> de las <i>GNU Compilar</i> para compilar <i>C</i> o <i>Fortran</i> desde la terminal. 

Sino bastara instalar:
</p>

* Xcode desde App Store.

<p align="justify">
Al decir <b>adaptación</b> de las <i>GNU Compiler</i> nos referimos a que Apple utiliza <a href="http://llvm.org/"><i>LLVM Compilar Infrastructure</i></a> pero eso no nos debe preocupar pues para el usuario es transparente. Podemos teclear desde la terminal <b>gcc</b> o <b>gfortran</b> sin problema.
</p>

## Paso 1:

<p align="justify">
	Creamos un archivo desde la terminal:
</p>

```
touch hola.f90
```

## Paso 2:

<p align="justify">
	Ingresamos el siguiente código:
</p>

```
PROGRAM HOLA
   PRINT *, '¡Hola, FORTRAN!'
END
```

## Contacto

Twitter: @ginppian


[Fuente 1](https://es.wikipedia.org/wiki/Anexo:Ejemplos_de_implementaci%C3%B3n_del_%C2%ABHola_mundo%C2%BB#En_Fortran)
[Fuente 2](https://gcc.gnu.org/wiki/GFortranUsage)