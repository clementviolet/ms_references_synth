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
eqnos-plus-name: équation
fignos-plus-name: figure
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

En écologie trophique il existe une boîte à outils de méthodes pour observer des interactions entre des proies et des prédateurs grâce à un certain nombre d'outils. Ces outils passent par de l'observation direct, de l'analyse de contenue stomacaux, les mesures d'isotopes stables, des contaminents ou bien encore des méthodes statistiques [@Majdi_2018]. Mais ces méthodes ne permettent pas de faire d'inferrence par rapport aux autres types d'interactions.

Ces dernières années, un ensemble de nouvelles méthodes statisques ont été développer pour estimer la distribution spatiale et ou temporelles à l'aide de données de co-occurence ou d'abondance, ce sont les *Spatial Distribution Models* (*SDM*). Ces méthodes peuvent être utiliser pour  analyser simultanément la distribution corrélée de plusieurs espèces [@Thorson_2016]. Ces nouvelles méthodes ont également l'avantage de pouvoir prendre en compte les interaction entre les espèces et éventuellement de les estimer. 

Dans les prochains paragraphes, il sera questions de quelques une de ces méthodes : *Latent Variable Model*, *Hierarchical Modelling of Species Communities*, *Gaussian copula graphical models* et quelques méthodes de machine learning. Enfin, dans une dernière partie, il s'agira d'avoir un regard critique sur les données de co-occurence et leurs apports pour prédire les interactions entre espèces.

## *Latent Variable Models*

Le but des *Latent Variable Models* (*LVM*) est de décrire les corrélation entre l'abondance des taxons en fonction de variables explicatives, ce genre de modèle fait parti d'une plus grande famille de modèles en écologie des communautés, nommés les *Joint species distribution models*. Les *LVM* sont des extensions des *Generalized Linear Model* (*GLM*) et ils incluent une forme d'effet aléatoire pour permettre de prendre en compte les corrélation d'abondance entre les espèces (+@eq:eq1). Dans le cas des *LVM*, l'effet aléatoire est inclu grâce à des variables latentes : c'est-à-dire des variables non mesurés par l'expérimentateur [@Warton_2015]. 

$$g(m_{ij}) = \alpha_i + \beta_{0j} + x_i'\beta_j + z_i'\lambda_j$$ {#eq:eq1}

$g()$ est la fonction de lien comme dans un GLM, qui relie la moyenne estimée au prédicteur linéaire. $m_{ij}$ est l'abdondance moyenne de l'espèce $j$ au site $i$. $\alpha_{i}$ est un terme facultatif qui s'ajuste en fonction de l'abondance relative ou de la richesse totale du site pour modéliser de l'abondance relative plutôt que sur l'abondance absolue.$x'$ est la transposé des données d'abondance pour chaque espèce $j$, $\beta_{0j}$ est l'ordonné à l'origine et $\beta_j$ est un vecteur de coefficient de régression estimé à partir des variables explicatives. Enfin $\lambda_j$ est un facteur de charge lié aux variables latentes $z_i$. Cette variable latente est traitée comme un facteur aléatoire, comme l'abondance en assumant que $y_{ij}|z_i \sim F(m_{ij}, \phi_j)$ et $z_i \sim N(0,1)$. Ainsi, la distribution de l'abondance connaissant la valeur de la variable latente suit une loi de probabilité caractérisé par une moyenne ($m_{ij}$) et un  paramètre de dispersion ($\phi_j$). La difficulté d'estimer un tel modèle reside dans l'estimation des variables latentes et des facteurs de charges, car non observées. Il faut alors avoir recourt à des priors ou de l'inférence bayésienne. Mais son intérêt résident également dans le fait que cette méthode permet de réduire le nombre de coefficient de corrélation à estimer lorsqu'elle est comparé à un *Generalized Linear Mixed Model* multivarié. Le temps de calcul d'un *LVM* est d'un dixième de celui d'un *Generalized Linear Mixed Model* pour un jeu de donnée de co-occurence à 65 colonnes et 75 lignes [@Warton_2015]. 

Les *LVM* permettent d'estimer les corrélation entre les espèces après avoir contrôllé l'effet de variables envrionnementales, mais égallement d'utiliser les variables latentes comme des axes d'ordination et bien entendu faire de l'inférence multivarié pour de la projection. Les *LVM* sont également intéressante pour inférer les interactions entre les espèces, puisque les variables latentes peuvent être interprété comme des variables comprenant les interactions entre les espèces au sein d'une même communautée.

Rapidement un package R est sorti pour permettre aux écologiste de mettre facilement en oeuvre les *LVM* comme *boreal* d'après les travaux de @Hui_2016.

## *Hierarchical Modelling of Species Communities*

Quelques années après le papier de @Warton_2015, @Ovaskainen_2017_procB proposèrent une extension des *JSDM* nommé *Hierarchical Modelling of Species Communities* (*HMSC*). Ce nouveau cadre statistique propose d'intégrer des données d'occurence ou d'abonndance, de données environnementales, le contexte spatio-temporel du plan d'échantillonage, des données de trait et de phylogénie +@fig:hmsc_summary.

![Schéma conceptule du cadre de modélisation statisque *HMSC*. Les rectangles oranges font référence aux données que peut entrer dans le modèle l'utilisateur et les élipse bleue font référence aux paramètres qu'il est possible d'observer. Adapté de @Ovaskainen_2017_procB.](figures/hmsc_summary.png){#fig:hmsc_summary}

Pour fonctionner, les *HMSC* ont besoin au minimum de données d'abondance (ou de co-occurence), ainsi que des données environnementales (matrices $X$ et $Y$ +@fig:hmsc_summary).

Ce genre de modèles peut répondre à un large éventaille de questions comme quelle part de la variance de l'abondance des espèces est due aux filtres environnemntaux, aux interactions biotiques et aux processus aléatoire ? Quelles sont les structures des réseaux d'interaction entre les espèces ? Ou bien encore est-ce que la présence de certaines espèces indiquent la présence d'autres ? [@Ovaskainen_2017_procB].

L'inférrence d'interaction est rendu possible grâce à l'estimation de de la matrice d'association $\Omega$ (+@fig:hmsc_summary). Cette matrice estime si deux espèces ont une probabilité d'occurence supérieur à celle du hasard. Pour $m$ espèce, cette matrice $\Omega$ a $m(m+1)/2$ paramètres à estimer, ce qui rend la tâche complexe lorsque $m$ est suffisament grand. Pour contourner ce problème, @Ovaskainen_2017_procB utilisent une méthode dérivée des *LVM*, ils utilisent les facteurs de charges associés aux variables latentes pour estimer la matrice $\Omega$. Bien que les auteurs soient d'accord sur le fait que ces facteurs de charge n'expriment pas directement des interaction au sens écologique du terme, ils sont utiles pour révéler des configurations où deux espèces sont présentes en même temps plus souvent que le hasard ne peut l'expliquer.

Pour utiliser ce cadre de modélisation, un package R a été développé pour mettre en place les analyses de type *HMSC* [@Tikhonov_2019]. Ainsi, ce type d'analyse a été mis en place sur les herbiers de zoostère[^1] (*Zostera marina*) par @Stark_2018. Ils ont ainsi pu mettre en évidence de signaux fort de co-occurence d'espèces antagonistes entre différents sites, ce qui leur a permis de supposer de fortes interactions biotiques qui pourrait se traduire par exemple, par de la compétition entre les espèces herbivore pour l'accès à la production primaire. Les auteurs font également l'hypohtèse que la structuration des communautés de *Zostera marina* peut également traduire un effet prioritaire[^2] important sur les herbiers plus récents.

[^1]: Un des milieux biogènes qui sera au coeur de mon stage.

[^2]: Effet que peut avoir une espèce particulière sur le développement d'une communauté, car elle s'est installée plus tôt sur le site.

## *Gaussian Copula Graphical Models*

Pour estimer l'interaction entre espèces @Popovic_2019 proposent l'utisation d'un nouveau cadre de modélisation statique : *Gaussian Copula Graphical Models* (*GCGM*). Ce nouveau type de modèle couple une distribussion multivariée gaussienne à une autre type de distribution marginale à choisir en fonction du type de donnée : distribution bionomiale pour des données de présence/absence, distribution de Poisson pour des données d'abondance, etc. Cette combinaison permet d'accéder au corrélations de co-occurence d'espèce pour tout type de données et l'utilisation d'une copule gaussienne permet d'utiliser des des modèles graphiques gaussien pour estimer les liens d'interactions entre les différentes espèces. Ainsi, ce nouveau type de méthode est capable d'utiliser tout types de données d'occurence utilisée en écologie. Sa grande flexibilité en fait une des forces de ce nouvel outil. Pour faciliter son utilisation, les auteurs de cet article ont mis à disposition un package R. Grâce au *GCGM* il est possible d'obtenir des graphes non-orientée qui permettent de voir les relations entre chaque espèces. Il est alors possible d'observer les interactions directe et indirecte entre les différentes espèces. De plus, l'obtention de graphes non orienté permet d'utiliser certaines mesures de la théorie des graphes pour permettre des interprétation plus large sur la structure du réseau écologique. Toutefois, quelques précautions sont à prendre avec l'analyse de cette méthode : les espèces qui semblent interragir entre elles peuvent répondre de la même façon à une variable environnementale non mesurée et l'absence d'interaction peut également être un artefac lié à un problème d'échantillonnage. 


## *Machine Learning*

Depuis quelques années, les écologues se sont emparés des méthodes de *Machine Learning* pour répondre à de vaste question. A partir de catalogue d'interactions il est possible de déterminer pour de nouvelles espèces, lesquelles sont susceptible d'interagir entre elles [@Desjardins-Proulx_2017 ; @Beauchesne_2017b] . L'algorithme retenu dans les deux cas a été celui des plus proches voisins (*KNN*). Bien que l'implémentation et la création du catalogue d'interaction permettant l'inférerance soit de nature différente, les auteurs de ces deux articles notent de très belles performances pour prédire les interactions trophiques. @Desjardins-Proulx_2017 montrent que leur algorithme est capable de prédire correctement la proie d'un prédateur plus de 50% du temps parmi un ensemble de plus de 800 proies possible. L'algorithme de @Beauchesne_2017b fait mieux en arrivant à prédire correctement les interactions entre 80% et presque 100% du temps. La différence de précision peut être en partie expliquée par la construction des catalogues d'interactions.

@Desjardins-Proulx_2017 ont également utilisé dans leur article un algorithme d'apprentissage supervisé, les *Random Forest*. Utilisant uniquement trois traits : la masse et deux variables portant sur les relations phylogénétiques, ils ont montré qu'il était possible de prédire correctement plus de 95% du temps les interactions et non-interactions dans un réseau trophique. 

Cette dernière approche a ouvert la piste à d'autres chercheurs qui se sont intéressés à prédire les interactions entre les plantes et les pollinisateurs [@Pichler_2019]. Dans leur article, les auteurs montrent par exemple que les algorithmes de *Random Forest* ou de *Deep Neural Network* sont capables de prédire correctement grâce aux traits près de 90% des interactions et surpassent d'autres méthodes statistiques plus classiques comme les *GLM*. De plus, ces algorithmes permettent aussi d'inférer quels sont les traits qui régulent les interactions entre les plantes et les oiseaux mouches sans avoir eu à faire d'hypothèses à priori sur le fonctionnement du système. Les auteurs mettent l'accent sur le fait que les algorithmes de *Machine Learning* offrent beaucoup d'avantages par rapport aux modèles de régression. Au vu du potentiel de ces algorithmes, les auteurs encouragent leur utilisation pour prédire les interactions dans d'autres types de réseaux d'interactions.


# Bibliographie
