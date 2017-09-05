# Laboratorio bioinformática 4


### Bruno Romero


-----



# Parte 1



----



#### ¿Qué cosas ofrece este portal? 


__R:__


+ `Ofrece servicios de filogenia en base al alineamiento de tres o más secuencias.  `



#### ¿Para qué tipo de usuario está diseñado?


__R:__


+ `Está diseñado para todo tipo de usuario: Usuarios sin experiencia, intermedios y avanzados, ya que posee distintos niveles de personalización. `


#### Menciona 5 tipos de análsis que se pueden realizar en el portal de acuerdo a la documentación


__R:__


+ `Multiple alignment, Alignment curation, Construcción del árbol filogenético, explorar secuencias homólogas usando BLAST y visualización del árbol filogenético. `



#### ¿A qué se refiere el paso de *Alignment curation* y para qué sirve?


__R:__



+ `Este paso corresponde con eliminar las zonas que no han sido alineadas en base al algoritmo de alineamiento previo. Es decir, que las secuencias que están en los extremos y que no están alineadas con las demás secuencias, no son consideradas para hacer el árbol filogenético. `




#### ¿Cuál es la diferencia entre BioNJ y Neighbor? (Pista: revisa la documentación)



__R:__



+ `La diferencia radica en la cantidad de información entregada por el programa y por la cantidad de taxas a analizar.`




#### Corre de nuevo las filogenias pero esta vez sin *Alignment curation*. ¿Cuál es el efecto en las filogenias?



__R:__




+ `Es demasiado diferente, tanto en las distancias filogenéticas como en el orden de las relaciones entre especies. Sin embargo, las especies que son más cercanas evolutivamente hablando, forman ciertos "grupos filogenéticos" que si se mantienen en ambos árboles. Sin embargo, el problema aparece cuando estos "grupos" se relacionan evolutivamente con otros y con especies que no están asociadas a un "grupo filogenético" (por ejemplo, pteropus alecto está en ambas filogenias realtivamente aislado). En general, lo que más cambia son las distancias evolutivas. `



#### Describe las diferencias entre las filogenias que has estimado: cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc.



__R:__



+ `Tal como mencioné anteriormente, lo que más cambió fueron las distancias evolutivas y la relación entre "grupos monofiléticos" (que en el texto anterior los referí como "grupos filogenéticos"). Las relaciones por homología que nacen a partir de la hipótesis de alineamiento mantiene a ciertas especies en <clusters>, los cuales interactúan en distinta forma con otros grupos. Además, el cambio más notorio se ve en los árboles hechos con ClustalW, ya que las diferencias de realizar los árboles con y sin el parámetro de curación, es enorme. Los patrones formados tanto de las relaciones como de las distancias han variado enormemente (Imagen 2 y 3). `





![Gblocks](https://github.com/CapitanFlint/Laboratorio-bioinfo-4/blob/master/foto%201%20gblocks.png)




__IMAGEN 1:__  Filogenia formada a partir de los parámetros ProbCons, GBlocks, MrBayes, y TreeDyn.




![sincurationprobcon](https://github.com/CapitanFlint/Laboratorio-bioinfo-4/blob/master/foto%202%20probcons%20sin%20curation.png)



__IMAGEN 2:__ Filogenia formada a partir de los parámetros ProbCons, [Sin alignment curation] , MrBayes, y TreeDyn.




![foto3clustalw](https://github.com/CapitanFlint/Laboratorio-bioinfo-4/blob/master/foto3clustalw.png)




__IMAGEN 3:__ Filogenia formada a partir de los parámetros ClustalW, "Remove positions with gaps", TNT, y TreeDyn




![foto4custalwsincurrar](https://github.com/CapitanFlint/Laboratorio-bioinfo-4/blob/master/foto4clustalwsincurar.png)




__IMAGEN 4:__ Filogenia formada a partir de los parámetros ClustalW, [alignemn sin curar] , TNT, y TreeDyn





# NOTA IMPORTANTE


Las fotos, a pesar de no tener el rut, claramente se ve mi usuario arriba en la spestañas. Además, el trabajo se lo entregué en el mismo lab, por lo que es imposible que haya obtenido las imágenes de otros trabajos.
(ya había sacado todas las fotos cuando avisó :( )
