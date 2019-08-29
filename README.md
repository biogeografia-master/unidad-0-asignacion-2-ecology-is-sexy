
<!-- Este .md fue generado a partir del .Rmd homónimo. Edítese el .Rmd -->
"Ecology is sexy"
=================

OK, llegamos donde teníamos que llegar.

Lee el Prefacio y la sección 1.3 de "Borcard, D., Gillet, F., & Legendre, P. (2018). *Numerical ecology with R*. Springer.". Deberás responder unas cuantas preguntas inocentes y algunos mandatos a continuación.

Preguntas/mandatos
------------------

-   ¿Cuántas citas aparecen en GoogleScholar (GS) para la obra de referencia? ¿Cuántas citas aparecen, igualmente en GS, en la edición de 2012?

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

    Tu respuesta, aquí: ...

-   Escribe un párrafo de no más de 2 líneas con tu opinión sobre lo leído.

    Tu respuesta, aquí: ...

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
  ', aparecían registradas', '\n',
  'las siguientes cuentas como miembros/as o colaboradores externos/as: ', '\n',
  paste(estudiantes, collapse = '\n'),
  sep = ''
)
```

    ## En fecha/hora: Thu Aug 29 11:34:35 2019, aparecían registradas
    ## las siguientes cuentas como miembros/as o colaboradores externos/as: 
    ## AbigailCP (M)
    ## BidelkisCastillo (M)
    ## dahianagb07 (M)
    ## emdilone (M)
    ## enrique193 (M)
    ## Erasbel05 (C)
    ## geofis (M)
    ## hoyodepelempito (M)
    ## jimenezsosa (M)
    ## Jorge-Mutonen (M)
    ## Mangoland (M)
    ## maritzafg (M)
    ## merali-rosario (C)
    ## ramosramos1886 (M)
    ## sanchez26 (M)
    ## victorcabsid (M)
    ## yanderlin (M)

-   **Nota**: Quienes aparecen con la coletilla "(C)" tienen estatus de "colaboradores externos", porque no han aceptado la invitación a formar parte como miembros de la organización "biogeografia-201902". Es necesario que acepten dicha invitación, que debieron haber recibido por correo en días pasados, para facilitar así las notificaciones.
