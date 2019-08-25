
<!-- Este .md fue generado a partir del .Rmd homónimo. Edítese el .Rmd -->
"Ecology is sexy"
=================

OK, llegamos donde teníamos que llegar.

Revisa la referencia "Borcard, D., Gillet, F., & Legendre, P. (2018). *Numerical ecology with R*. Springer.". Preparé preguntas y mandatos según secciones del libro de referencia. Responde a cada ítem abajo.

Preguntas, mandatos
-------------------

-   Escribe un párrafo de no más de 10 líneas conteniendo: resumen de las respuestas y tu valoración/opinión.

-   ¿Cuántas citas aparecen en GoogleScholar para la obra de referencia? ¿Cuántas citas aparecen, igualmente GS, en la edición de 2012?

Tu respuesta, aquí: ...

### Sobre el prefacio

Lee el prefacio y, a continuación, responde estas preguntas:

-   ¿Describe qué significa para ti que los autores se refieran a "audiencias con buena predisposición"? ¿Por qué entiendes que los autores introducen dicho asunto?

Tu respuesta, aquí: ...

-   ¿Entiendes que existe renuencia a cuantificar la naturaleza? ¿Por qué? En caso afirmativo, ¿Sería esto un problema? ¿Por qué?

Tu respuesta, aquí: ...

-   Los autores aseguran que durante décadas los/as ecólogos/as solían contratar a una "persona estadística" para todo el rollo numérico. Según los autores, ¿Qué problemas/inconvenientes tenía/tiene esta práctica? ¿Qué solución/soluciones proponen?

Tu respuesta, aquí: ...

-   En la implementación del cuantitativismo en ecología dentro del aula, ¿Qué "ingredientes" echaban de menos los autores?

Tu respuesta, aquí: ...

-   Tras responder la pregunta anterior, lee el *abstract* del artículo "Lai, J., Lortie, C. J., Muenchen, R. A., Yang, J., & Ma, K. (2019). Evaluating the popularity of R in ecology. Ecosphere, 10(1), e02567.". ¿Algo más que quieras añadir (en este caso, vale opinar)?

Tu respuesta, aquí: ...

-   Tras lo que has leído en el prefacio, ¿podrías precisar diferencias y puntos de encuentro entre ecología y ecologismo?

Tu respuesta, aquí: ...

### En el capítulo 1 ...

Lee el último párrafo de la sección "*1.3 Readership and Structure of the Book*" y, a continuación, realiza lo siguiente:

-   En dos líneas, resume el contenido del libro.

Lista de estudiantes en la organización
---------------------------------------

``` r
estfuente <- paste0(
  'https://raw.githubusercontent.com/biogeografia-201902/',
  'miembros-y-colaboradores/master/suscripciones_github.txt'
)
estudiantes <- readLines(estfuente)
cat(
  'En fecha/hora: ',
  date(),
  ', aparecían como registradas', '\n',
  'las siguientes cuentas como miembros/as o colaboradores externos/as: ', '\n',
  paste(estudiantes, collapse = '\n'),
  sep = ''
)
```

    ## En fecha/hora: Sun Aug 25 17:33:18 2019, aparecían como registradas
    ## las siguientes cuentas como miembros/as o colaboradores externos/as: 
    ## AbigailCP
    ## BidelkisCastillo
    ## enrique193
    ## Erasbel05
    ## jimenezsosa
    ## Jorge-Mutonen
    ## merali-rosario
    ## ramosramos1886
    ## victorcabsid
    ## yanderlin
    ## dahianagb07
    ## geofis
    ## hoyodepelempito
    ## Mangoland
    ## maritzafg
    ## sanchez26
