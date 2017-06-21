Fortran - ¡Hola Mundo!
===========

## Descripción:

<p align="justify">
	Es un lenguaje de programación de alto nivel de propósito general, procedimental e imperativo, que está especialmente adaptado al cálculo numérico y a la computación científica. Desarrollado originalmente por IBM en 1957 para el equipo IBM 704, y usado para aplicaciones científicas y de ingeniería, el FORTRAN vino a dominar esta área de la programación desde el principio y ha estado en uso continuo por más de medio siglo en áreas de cómputo intensivo tales como la predicción numérica del tiempo, análisis de elementos finitos, dinámica de fluidos computacional (CFD), física computacional y química computacional. 

Es uno de los lenguajes más populares en el área de la computación de <b>alto rendimiento</b> y es el lenguaje usado para programas que evalúan el desempeño (benchmark) y el ranking de los supercomputadores más rápidos del mundo.</p>


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

[Fuente 0](https://es.wikipedia.org/wiki/Fortran)<br>
[Fuente 1](https://es.wikipedia.org/wiki/Anexo:Ejemplos_de_implementaci%C3%B3n_del_%C2%ABHola_mundo%C2%BB#En_Fortran)<br>
[Fuente 2](https://gcc.gnu.org/wiki/GFortranUsage)