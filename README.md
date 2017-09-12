# Laboratorio bioinformática 4

## Parte 1

####  ¿Qué cosas ofrece este portal?

Esta plataforma está diseñada para proporcionar servicios de filogenia  de alto rendimiento, realizando un análisis filogenético en base al alineamiento de tres o más secuencias.

#### ¿Para qué tipo de usuario está diseñado?

Está diseñado para todo tipo de usuarios desde aficionados filogenéticos, hasta aquellos que buscan análisis mas sofisticados, “la filosofía principal de Phylogeny.fr es ayudar a los biólogos sin experiencia en la filogenia en el análisis de sus datos de una manera robusta."
 
 ####  Menciona 5 tipos de análisis que se pueden realizar en el portal de acuerdo a la documentación
Alineación múltiple
 Construcción del árbol filogenético 
Filogenia con máxima verosimilitud, 
Estimaciones de soportes de clados
Alineación múltiple mediante información estructural

#### ¿A qué se refiere el paso de Alignment curation y para qué sirve?

Este paso corresponde a la eliminación de las zonas no alineadas en base  al algoritmo de alineamiento previo, las zonas eliminadas  no son consideradas en la realización del árbol filogenético.

#### ¿Cuál es la diferencia entre BioNJ y Neighbor? (Pista: revisa la documentación)

La diferencia importante radica  en la cantidad de información que  entrega el programa y también  la cantidad de taxas que puede analizar, BioNj tiene una capacidad muchas más taxas que Neighbor en una relación de <5000 (BioNj)  vs <500 (Neighbor).

#### Corre de nuevo las filogenias pero esta vez sin Alignment curation. ¿Cuál es el efecto en las filogenias?

 El efecto de correr las filogenias sin alignment curation presenta diferencias importantes; se observan diferencias en el orden de las especies y  sus relaciones, como también en las distancias evolutivas son notablemente diferentes.

#### Describe las diferencias entre las filogenias que has estimado: cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc.

Se visualizan diferencias significativas en relación a las distancias evolutivas y a sus grupos monofileticos, cabe destacar que los análisis con parámetros como probcons y con clustalw son signifcativamente diferentes ya que se pueden visualizar grupos monofileticos que no están presentes en ambos análisis. Se puede apreciar que en clustalw especies están muy relacionadas entre sí y en el probcons se ven distantes, estableciendo una diferencia fundamental en los análisis.



![1](https://raw.githubusercontent.com/constanzaortega/laboratorio-4/master/21641453_10214335214602116_580221554_n.jpg)


IMAGEN 1: Filogenia formada a partir de los parámetros ProbCons, GBlocks, MrBayes, y TreeDyn


![2](https://raw.githubusercontent.com/constanzaortega/laboratorio-4/master/21641445_10214335215922149_1386964157_n.jpg)


IMAGEN 2: Filogenia formada a partir de los parámetros ProbCons, [Sin alignment curation] , MrBayes, y TreeDyn.


![3](https://raw.githubusercontent.com/constanzaortega/laboratorio-4/master/21623989_10214335218042202_283444414_n.jpg)


IMAGEN 3: Filogenia formada a partir de los parámetros ClustalW, "Remove positions with gaps", TNT, y TreeDyn


![4](https://raw.githubusercontent.com/constanzaortega/laboratorio-4/master/21624258_10214335222282308_1597776692_n.jpg)


IMAGEN 4: Filogenia formada a partir de los parámetros ClustalW, [alignemn sin curation] , TNT, y TreeDyn


## Bibliografia


1.- http://www.phylogeny.fr/alacarte.cgi?workflow_id=510f9528b2ea33bd7eb84d9613d85901&tab_index=last


2.-http://www.phylogeny.fr/documentation.cgi




