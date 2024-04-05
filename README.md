# Sistema Electoral del Poder Ejecutivo en América Latina y sus Reformas

Bienvenidos/as al repositorio GitHub de la base de datos "Sistema Electoral del Poder Ejecutivo en América Latina y sus Reformas", creada por la Dra. Flavia Freidenberg y mantenida por integrantes del Observatorio de Reformas Políticas en América Latina.

## Contenidos

-   [Resumen](#resumen)
-   [Descripción](#descripción)
-   [Citado](#citado)

## Resumen

Esta base de datos contiene información sobre las reformas electorales a la normativa que regula el sistema electoral de los poderes ejecutivos nacionales de 18 países de América Latina. En la base de datos hay información sobre las modificaciones en la fórmula electoral, la existencia de segunda vuelta, las mayorías necesarias en primera y segunda vuelta, los años de duración del mandato y la posibilidad de reelección.

La revisión de la normatividad se realizó a partir del año de la transición a la democracia de cada país, con base en lo planteado por Alcántara; Paramo; Freidenberg y Déniz (2006). En el caso de los países con procesos de cambio político graduales, se utiliza como base el año de inicio de la tercera ola de la democracia en América Latina (Huntington, 1991).

Integrantes del Observatorio de Reformas Políticas en América Latina recopilaron y codificaron la información. Las personas responsables de la recopilación de los datos son Karolina Monika Gilas (Facultad de Ciencias Políticas y Sociales, UNAM) y Luciana Modica (Universidad Nacional de Río Cuarto, Argentina), mientras que la persona responsable de la codificación de los datos es Luciana Modica (Universidad Nacional de Río Cuarto, Argentina).

## Descripción

El directorio `./Data/` contiene el archivo `./Data/DD_SEEjecutivo` en el cual se encuentra toda la información relevante respecto a la base de datos del sistema electoral del Poder Ejecutivo. En específico, la base de datos se compone de las siguientes variables:

-   `país`: nombre del país en el cual se llevó a cabo la reforma al régimen electoral ejecutivo en América Latina.
-   `cowcode`: código del país de acuerdo con la codificación de “Correlates of War”  disponible en: https://correlatesofwar.org/data-sets/cow-country-codes.
-   `siglas_pais`: siglas del país de acuerdo con el código de tres letras ISO (por ejemplo: ARG, MEX, SAL) disponible en: http://utils.mucattu.com/iso_3166-1.html.
-   `consec_reforma_pais`: registra el número consecutivo de las reformas al régimen electoral ejecutivo en cada país de América Latina. Ejemplo: Peru_1 Peru_2, Peru_3, Peru_4.
-   `año`: año calendario al que corresponde la reforma al régimen electoral del ejecutivo en cada país de América Latina entre 1978-2021.
-   'form_electoral': indica el modo en que se define la elección del poder ejecutivo nacional. Sus valores son [1]: Colegio electoral; [2]: Mayoría relativa; [3]: Mayoría absoluta; [4]: Doble vuelta; [5]: ley de lemas.
-   `exist_2da_vuelta`: indica la existencia o inexistencia de la segunda vuelta en las elecciones para el poder ejecutivo nacional. Sus valores son No [0]: la normativa no considera la existencia de segunda vuelta electoral y Sí [1]: la normativa considera la existencia de segunda vuelta electoral.
-   `mayor_1vuelta`: indica la mayoría necesaria para ganar la elección del poder ejecutivo nacional en primera o única vuelta. Sus valores son Mayoría relativa [1]: mayoría relativa en única vuelta; >50% [2]: mayor al 50% de los votos; >50% o 25 pts. [3]: mayor al 50% de los votos o una diferencia de 25 puntos con el segundo puesto; >50% o 40% + 10 pts. [4]: mayor al 50% de los votos o 40% más una diferencia de 10 puntos con el segundo puesto; >45% [5]: mayor al 45% de los votos; >45% o 40% + 10pts. [6]: mayor al 45% de los votos o 40% más una diferencia de 10 puntos con el segundo puesto; >40% [7]: mayor al 40% de los votos; >40% o 35% y 5 pts. [8]: mayor al 40% de los votos o 30% más una diferencia de 5 puntos con el segundo puesto.
-   `mayor_2vuelta`: indica la mayoría necesaria para ganar la elección del poder ejecutivo nacional en segunda vuelta. Sus valores son Mayoría absoluta [1]: el poder ejecutivo es electo con mayoría absoluta en la segunda vuelta; Mayoría en el Congreso [2]: el poder ejecutivo es electo con mayoría en el Congreso.
-   `años_mandato`: indica la duración del mandato del poder ejecutivo nacional en años.
-   `reelección`: indica la existencia o inexistencia de la reel ección del poder ejecutivo nacional. Sus valores son No [0]: la normativa no considera la existe de reelección y Sí [1]: la normativa considera la existe de reelección.

## Citado

``` r
Freidenberg, Flavia. Dir., 2022, “Sistema electoral del poder ejecutivo en América Latina y sus reformas”, Observatorio de Reformas Políticas en América Latina (1978-2021). Ciudad de México: Instituto de Investigaciones Jurídicas (IIJ-UNAM) y Washington, D.C.: Secretaría para el Fortalecimiento de la Democracia de la Organización de los Estados Americanos (SFD/OEA), V2. DOI: https://doi.org/10.6084/m9.figshare.16869293.v2 
```