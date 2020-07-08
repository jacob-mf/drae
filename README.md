# drae
[![Build Status](https://travis-ci.org/jacob-mf/drae.svg?branch=master)](https://travis-ci.org/jacob-mf/drae)
[![Code Climate](https://codeclimate.com/github/jacob-mf/drae/badges/gpa.svg)](https://codeclimate.com/github/jacob-mf/drae)

Drae - Comando para el uso del diccionario de la RAE en la consola Linux | RAE Spanish dictionary on your Linux term
Programa en bash para el uso del diccionario de la RAE en consola | Bash application to show RAE dictionary entries through the console
* RAE: Real Academia Española (Royal Spanish Academy)

Probado sobre Linux Debian Buster 10.3 | Tested over Linu Debian Buster 10.3
GNU bash, versión 5.0.3(1)-release (x86_64-pc-linux-gnu)
Requisitos:  | Requirements:
Usa paquete 'elinks' (navegador de Internet por texto, versión 0.13.GIT) | Elinks (Text web browser version 0.13.GIT)
Comando 'sed' para lo más complicado de la tarea (GNU sed) 4.7) | Bash command 'sed' (sed (GNU sed) 4.7)
Accede al directorio temporal /tmp el sistema de ficherros | Need access to the temporary directory /temp in the machine's file system 

Aplicación basada en otra antigua 'drae' y en el proyecto: | Based on the following project:
 <https://github.com/sardach/rae-cli> 
Ambas inspiraciones importantes de esta aplicación, y a cuyos autores queremos homenajear aquí.
 Muchas gracias. | Thanks a lot for the inspiration.
Todas las definiciones son propiedad de la Real Academia Española. | All the definitions provided are trademarks of the Royal Spanish Academy (RAE).

Instalación: | Install:

```bash
$ chmod +x drae
```

Uso | Usage:
```bash
luis@pc ~ $ drae consola
 consola

   Del fr. console.

   1. f. Mesa hecha para estar arrimada a la pared, comúnmente sin 
 cajones y con un segundo tablero inmediato al suelo.

   2. f. Dispositivo que, integrado o no en una máquina, contiene los
   instrumentos para su control y operación.

   3. f. videoconsola.

             Real Academia Española © Todos los derechos reservados

luis@pc ~ $ drae --help
DRAE 0.11, el Diccionario de la Real Academia Española desde la consola.

Modo de empleo: drae [OPCIÓN] [PALABRA]
 Muestra la definición del diccionario acerca de la PALABRA (máximo una)
 introducida (algunas opciones no requieren del párametro PALABRA).

Opciones disponibles en la versión actual:

   drae PALABRA      muestra la definición de la palabra, si existe,
                     o muestra otras que pudieran estar relacionadas

   drae -A           muestra la definición de una palabra al azar
   drae -a PALABRA   muestra anagramas de la palabra (otras palabras
                     formadas con las mismas letras).
   drae -C [LETRAS]  muestra palabras (lemas) que contengan
                     las letras introducidas.
   drae -p           muestra la palabra del día de la RAE                 
   drae -e [LETRAS]  muestra palabras que empiecen en las letras dadas
   drae -t [LETRAS]  muestra palabras que terminen con las letras dadas
   drae -c [VERBO]   muestra las posibles conjugaciones del verbo
   drae  --ayuda     muestra esta pantalla
   drae --version    muestra la versión instalada del programa

Ejemplos:
    drae albos       se muestra a la entrada del diccionario de la
                     palabra "albo, ba", aunque se consulte el plural
    drae -e cada     se enumeran palabras que empiezan por: "cada"
          
Aplicación basada en otra antigua 'drae' y en el proyecto:
 <https://github.com/sardach/rae-cli> 
 Inspiraciones ambas de esta aplicación, y a cuyos autores queremos
 homenajear aquí. Muchas gracias. 
Todas las definiciones son propiedad de la Real Academia Española.
Si lo desea puede informar sobre errores y sugerencias en:
 <https://gitlab.com/drae>
¡Salud!

 ```

Si lo desea puede informar sobre errores y sugerencias en:
 <https://github.com/jacob-mf/drae>
 <https://gitlab.com/caldez/drae>

## LICENSE
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Lesser General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later versions.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
