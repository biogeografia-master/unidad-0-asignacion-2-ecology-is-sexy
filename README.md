
<!-- Este .md fue generado a partir del .Rmd homónimo. Edítese el .Rmd -->
Lista de estudiantes en la organización
---------------------------------------

``` r
estfuente <- 'https://raw.githubusercontent.com/biogeografia-201902/miembros-y-colaboradores/master/suscripciones_github.txt'
estudiantes <- readLines(estfuente)
cat(
  'En fecha/hora: ',
  date(),
  ', estaban registradas las siguientes cuentas como miembros/as o colaboradores externos/as: ',
  paste(estudiantes, collapse = ', '),
  sep = ''
)
```

    ## En fecha/hora: Sun Aug 25 15:39:06 2019, estaban registradas las siguientes cuentas como miembros/as o colaboradores externos/as: AbigailCP, BidelkisCastillo, enrique193, Erasbel05, jimenezsosa, Jorge-Mutonen, merali-rosario, ramosramos1886, victorcabsid, yanderlin, dahianagb07, geofis, hoyodepelempito, Mangoland, maritzafg, sanchez26

"Ecology is sexy"
=================

OK, llegamos donde teníamos que llegar.

Revisa la referencia "Borcard, D., Gillet, F., & Legendre, P. (2018). *Numerical ecology with R*. Springer.". Preparé preguntas y mandatos según secciones del libro de referencia. Responde a cada una.

Preguntas, mandatos
-------------------

1.  Escribe un párrafo de no más de 10 líneas conteniendo: resumen de las respuestas, tu valoración/opinión

    Tu respuesta, aquí: ...

    ### Prefacio

2.  ¿Describe qué significa para ti que los autores se refieran a "audiencias con buena predisposición"? ¿Por qué entiendes que los autores introducen dicho asunto?

    Tu respuesta, aquí: ...

3.  ¿Entiendes que existe renuencia a cuantificar la naturaleza? ¿Por qué? En caso afirmativo, ¿Por qué sería esto es un problema?

    Tu respuesta, aquí: ...

4.  Los autores aseguran que durante décadas los/as ecólogos/as solían contratar a una "persona estadística" para todo el rollo numérico. Según los autores, ¿Qué problemas/inconvenientes tenía/tiene esta práctica? ¿Qué solución/soluciones proponen?

    Tu respuesta, aquí: ...

5.  En la implementación

    ### Contenido

6.  Con lo visto leído en el prefacio, ¿podrías precisar diferencias y puntos de encuentro entre ecología y ecologismo?
