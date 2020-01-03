---
authors: Clément Violet
documentclass: report
classoption: 
  - a4paper
  - oneside
dates: Semestre 9
polyglossia-lang:
  name: french
geometry:
  - left = 2cm
  - right = 2cm
  - top = 2cm
  - bottom = 2cm
mainfont: Lato
fontsize: 12pt
toc: true
linestretch: 1.5
subtitle: UE Analyse Bibliographique
tablenos-plus-name: tableau
tablenos-star-name: Tableau
---

# Introduction

Les interactions sont un des éléments clés de voute de la structure des communautés biologiques. Ainsi, dès le début de l'écologie moderne, les interactions sont apparues comme l'un des deux éléments importants dans la lutte pour le plus apte [@Darwin_2004]. Ainsi, à des échelles temporelles et spatiales réduites, les interactions sont le principal facteur de la biodiversité [@Benton_2009], c'est l'hypothèse de la *Reine Rouge* [@Van_Valen_1973]. 

Cependant, les connaissances sur les interactions intraspécifiques et interspécifiques sont encore aujourd'hui très lacunaires [@Morales_Castilla_2015 ; @Rosado_2016]. Ce manque de connaissance peut s'expliquer par le fait qu'il est actuellement impossible d'observer les interactions entre les espèces. Par exemple, un écosystème avec seulement sept espèces différentes peut donner lieu à l'observation de 42 directes interactions et plus de 13 000 interactions indirectes [@Morales_Castilla_2015].

La caractérisation et l'inférence des interactions entre les espèces peuvent sembler alors une tâche qui n'a que peut d'intérêt au vu de sa complexité. Toutefois, il existe des preuves dans la littérature que les interactions peuvent affecter l'aire de répartition et la co-distribution des espèces à des échelles spatiales locales, voire continentales. De plus, les interactions pourraient également moduler les réponses biologiques des espèces face aux changements environnementaux [@Morales_Castilla_2015].  De plus en plus de recherches se penchent ainsi sur la prédiction du fonctionnement des écosystèmes face aux changements globaux. C'est pourquoi la prédiction des interactions entre les espèces d'un même écosystème devient un enjeu majeur en écologie des communautés [@Montoya_2010].

# Les interactions en écologie

## Différentes interactions

Une interaction pourrait être définie comme l'action d'une première espèce sur une seconde. De fait, il existe plusieurs façons de décrire les interactions en écologie : les interactions peuvent varier selon leur type (antagoniste ou facilitatrice), leur forcent (faible ou forte) ainsi que leur symétrie (symétriques ou asymétriques) et leur mode d'action (direct ou indirect) [@Wootton_1994 ; @Morales_Castilla_2015]. Cette définition n'englobe pas une échelle écologique précise : les interactions peuvent être observées au niveau des individus, de populations ou bien encore d'espèces.

<!-- Classiquement, les interactions sont représentées de manière mécaniste notamment à l'aide de graphes : si un prédateur se trouve face à une proie, le prédateur consommera forcément la proie. Toutefois, cette représentation mécaniste n'est pas forcément la plus adéquate pour représenter des interactions. Un changement de paradigme serait donc intéressant pour représenter les interactions en termes de probabilités d'occurrence [@Poisot_2016]
-->
Dans un premier temps, nous nous intéresserons aux interactions directes,  puis aux interactions indirectes.

## Les interactions directes

Historiquement, le premier type d'interaction étudié a été les interactions directes grâce à l'observation de réseaux trophique, il y a plus d'un siècle [@Dunne_2006]. Une interaction directe est définie comme une interaction physique entre deux individus : un donneur et un receveur. [@Wootton_1994]. Dans les années 70, c'est l'étude des interactions hôtes-parasites qui a connu un rapide gain d'intérêt. Enfin, au début des années 2000, ce sont les réseaux mutualistes qui ont été mis sur le devant de la scène par les chercheurs [@Poisot_2019]. C'est pourquoi traditionnellement les réseaux écologiques sont subdivisés dans ces trois catégories citées au-dessus [@Ings_2009]. Toutefois, il est possible de définir plus d'interactions directes comme le montre le +@tbl:1.


| Type d'interaction et nature de l'effet |                    Exemple Biologique                  |
| :-------------------------------------- | :----------------------------------------------------- |
|  Mutualisme (+, +)                      |  Fleurs et insectes polinisateurs                      |
|  Prédation / Parasitisme (+, -)         |  Lions et gnous                                        |
|  Commensalisme (+, 0)                   |  Crevettes nettoyeuses et les muraenidae               |
|  Amensalime (0, -)                      |  Piétinement des pelouses par l'Homme                  |

Table: Exemple des différents types d'interaction qu'il est possible de rencontrer en écologie. L'espèce qui effectue l'interaction est dans la partie gauche de la parenthèse et celle qui subit l'interaction est sur la partie droite de la parenthèse. L'effet de l'interaction est représenté par un symbole. Adapté de @Morales_Castilla_2015. {#tbl:1}


## Les interactions indirectes

Les interactions indirectes sont forment la seconde grande classe d'interaction qui structurent les communautés écologiques. Les interactions indirectes peuvent être définies comme l'effet d'un individu ou d'une espèce émetteur d'une interaction sur une autre (receveur) par la médiation d'un troisième transmetteur. @Wootton_1994 démontre que les interactions indirectes peuvent se propager de deux manières différentes : par une chaîne d'interaction ou par une modification des interactions. 

Une chaîne d'interaction est décrite comme l'interaction d'une espèce A sur une autre espèce B via une espèce transmettrice. Par exemple, une espèce peut réduire l'abondance de sa proie, réduisant ainsi la base alimentaire des autres consommateurs de la proie [@Wootton_1994].

La modification des interactions se produit lorsque le changement d'abondance d'une espèce A peut indirectement affecter l'abondance d'une espèce B en modifiant l'interaction entre l'espèce  B et une espèce C. @Wootton_1994 donnent l'exemple suivant : l'augmentation de la densité de la végétation peut augmenter indirectement l'abondance d'une espèce prédatée en lui permettant de se cacher de ses prédateurs, réduisant ainsi l'intensité de l'interaction proie-prédateur.

@Menge_1995 a proposé sept grands types d'interactions indirectes +@fig:interactions_menge :

 - Prédation clé de voute : interaction observée lorsque l'abondance d'un prédateur augmente indirectement l'abondance des concurrents de sa proie par la consommation de ladite proie ;
 - Cascade trophique : augmentation de l'abondance d'une espèce causée par le contrôle de son prédateur immédiat par un autre prédateur ;
 - Exploitation concurrentielle : réduction de l'abondance d'un consommateur résultant de la réduction de l'abondance sa proie par une autre espèce de consommateur ;
 - Compétition : réduction de l'abondance d'une espèce résultant de l'augmentation de l'abondance d'une deuxième espèce qui augmente la prédation par un prédateur commun ;
 - Mutualisme indirect : Changements positivement corrélés de l'abondance de deux espèces résultant de la prédation de chacune sur la proie principale de l'autre ;
 - Commensalisme indirect : résulte du fait qu'une des deux espèces de prédateurs dans un schéma de mutualisme indirect à un régime alimentaire plus large et se nourrit également de la proie principale de l'autre espèce de prédateur dans le schéma de mutualiste indirect ;
 - Facilitation d'habitat : un organisme améliore indirectement l'habitat d'un deuxième en modifiant l'abondance d'une troisième espèce.

![Schéma des différents types d'effets indirects. P, prédateur ; H, herbivore ; B, espèce basale. Les flèches pleines représentent les effets directs, les flèches en pointillés représentent les effets indirects. +, effet positif ; -, effet négatif. p, prédation ; c, compétition d'interférence ; f, apport de nourriture ; if, inhibition de la prise alimentaire. Adapté de @Menge_1995.](figures/indirect_interaction_menge.png){#fig:interactions_menge}

# Caractéristiques des interactions

<!-- Au cours des années, les scientifiques ont développés des approches différentes pour comprendre comment les interactions structuraient les communautés en écologie. Une -->

## Réseau d'interaction et théorie des graphes

Les réseaux écologiques d'interactions peuvent être représentés à l'aide de graphes. Les graphes sont des constructions mathématiques constituées de deux ensembles : les noeuds et les arêtes  qui représentent les connexions entre des paires de noeuds [@Dale_2010]. Ces outils mathématiques facililent la représentation des interactions, chaque noeud étant une espèce et chaque arrête représentant une interaction. Les arrêtes peuvent être orienté ou non. Si le graphe est orientés, alors la direction de l'interaction entre l'espèce emetrice et receveuse de l'interaction est indiquée par l'arrête sous la forme d'une flêche [@Dunne_2006 ; @Dale_2010 ; @Delmas_2018]. <!-- Ainsi, si deux espèces peuvent intéragir ensemble avec cette représentation, alors elles intéragissent obligatoirement. -->

L'utilisation de graphes en écologie permet d'utiliser un ensemble d'outils développés par les mathématiciens pour mieux comprendre les réseaux complexe. Il existe ainsi des outils permettant de décrire comment les espèces intéragissent au sein d'une communauté, quelle est le rôle de chaque espèce dans la communauté [@Delmas_2018] etc. Aussi pour ce travail, il ne sera question dans les prochains paragraphes que de quelques uns des outils permettant de décrire comment les espèces intéragissent entre elles.

Une des propriétés basique d'un graphe découle de sa définition : le nombre de noeuds. Dans le cas d'un réseau écologique, chaque noeud est associé à une espèce [@Dunne_2006 ; @Delmas_2018]. $S$ représente ainsi la riche spécifique d'une communautés. De même, il est possible de définir le degré $deg$ comme le nombre d'arrête pour un noeud et $L$ comme le nombre d'arrêtes tout un réseau écologique. C'est ainsi qu'il est possible de déduire la densité d'un réseau écologique en appliquant le rapport $\frac{L}{S}$ qui indique le nombre de lien qui est attendu pour une espèce prise au hasard. Toutefois, la mesure de la densité n'est pas un indicateur satisfaisant, en effet il ne représente pas l'ensemble des liens possible dans un réseau d'intéraction. C'est alors que @Martinez_1992 proposa une autre mesure la connectance. La formule de la connectance $C = \frac{L}{m}$ varie selon le type de réseau considérée : si les espèces peuvent intéragir avec elles mêmes, alors $m = S^2$ dans le cas contraire $m = (S - 1)^2$. La propriété de la connectance est importante pour les réseaux écologiques, car elle permet de donner des indications quant à la fragilité du réseau.

La distribution des degrés est la mesure qui donne la probabilité qu'une espèce ait $k$ interaction. Cette mesure se calcule de la manière suivante : $P(k) = N_k / S$ avec $N_k$ le nombre de noeuds ayant $k$ arrêtes. La distribution de degrés d'un graphe est une mesure permettant l'identification des espèces clés de voutes potentielles [@Dunne_2006]. De plus, les degrés d'un graphe peuvent, dans le cas d'un graphe orienté être décomposés en arrêtes entrantes et sortantes d'un noeud. Ainsi, il est possible de déterminer d'autres mesures commme le nombre de prédateurs et le nombre d'espèces prédatés [@Delmas_2018].

Les réseaux d'intéractions peuvent être également décomposés en sous graphes plus petits : les motifs. Les motifs sont des assemblages de trois noeuds, il en existe 13 différents pour les graphes orientés. La fréquence de ces différents motifs donne aux biologistes des informations sur la structure des réseaux d'interactions, puisque certains motifs sont présent à une fréquence différente de celle du hasard. Les motifs sont considérés comme la brique de construction élémentaire d'un réseau d'interaction. L'étude des motifs se trouve particulièrement efficace pour étudier les processus déterminant l'assemblage et le désasemblage des communautés ou bien encore pour étudier le rôle trophique d'une espèce et lier ce lien avec la stabilité du réseau d'interaction [@Dunne_2006 ; @Delmas_2018].

Un dernier outil de mesure de la structure des réseaux d'interaction issue de la théorie des graphes est l'intervalité. Pour calculer l'intervalité d'un réseau d'interaction biologique, il faut trouver un trait commun à tous les noeuds pour lequel il est possible d'ordonné tous les noeuds. Cela peut être fait pour les réseaux trophique à l'aide de la taille ou de la masse moyenne d'un individu. Les réseaux d'intéractions qui peuvent être entièrement décrit par une seule dimmension (un trait) sans qu'il y ait d'ex-aequo sont dit "intervalles" [@Delmas_2018]. Les réseaux trophiques étudidées par @Eklof_2013 d'une taille inférieur à 250 espèces se sont montrés être "intervalles", ainsi les réseaux trophiques sont considérés comme quasi-intervalles, puisqu'un nombre réduit de dimension permert d'expliquer leur structure. L'intervalité offre une perspective intéressante à l'utilisation de certains outils de réduction de la dimensionalités pour expliquer la structure des réseaux d'interaction en écologie à l'instar de l'ACP utilisée par @Vermaat_2009.

Toutefois, ces mesures d'analyse de la structure des réseaux d'interaction ont une limite important. L'hypothèse sous-jacente est la suivante : si deux espèces dans un graphes sont reliées entre elles par une arrête, alors ces deux espèces intéragissent forcément ensemble. Hors les interactions entre espèces sont des entités dynamiques, elles varient en fonction de l'espace et du temps et d'effets comportementaux ainsi que stochastiques [@Poisot_2014]. C'est ainsi que @Poisot_2016 propose de un changement de paradigme en ne se posant plus la question si deux espèces intéragissent, mais plutôt de savoir quelle est la probabilité qu'elles interagissent ? Dans ce même article, les auteurs proposent de redéfinir l'ensemble de ces métriques pour prendre en compte la nature stochastique des interactions en écologie.

<!-- ## Données de co-occurences -->


# Prédire les interactions


# Template

## List

1. one fish
2. two fish
3. red fish
4. blue fish

## Equation
There is an equation, which we can cite with {@eq:eq1}.

$$J'(p) = \frac{1}{\text{log}(S)}\times\left(-\sum p \text{log}(p)\right)$$ {#eq:eq1}


We can do tables:

| Column 1 | Column 2 |      Column 3    |
| -------- | :-------:| ---------------: |
| c1       |    c2    |       $\alpha$   |

Table: Demonstration of a simple table. {#tbl:toto}

The first column is neat, the second centered and the third right-aligned. We can also cite table with {@tbl:toto}

## Figures

<!--
![This is the legend of the figure](figures/biomes.png){#fig:biomes}

We can refer to @fig:biomes. 
-->

## Code?

Yes

~~~ julia
for i in eachindex(x)
  x[i] = zero(eltype(x)) # Don't do that
end
~~~

# Bibliographie
