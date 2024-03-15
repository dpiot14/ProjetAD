# ProjetAD

## Principe du projet : 
Ce projet en Analyse de données à pour objectif d'étudier un jeu de données sur les chargements des stations de Velib dans la ville de Paris sur une période d'une semaine entre le 2 et le 7 septembre.

Un premier jeu de données contient les taux de chargements des stations de distribution des vélos.

* Un taux de chargement à 0 indique que la station est vide et qu'aucun vélo n'est disponible.
* Un taux de chargement à 1 indique que la station est pleine et que tous les vélos qu'elle peut contenir sont disponibles.
  
Un second jeu de données contient les coordonnées (logitude et latitude) associées à chaque station, ainsi qu'un élément Bonus.

* Un bonus à 1 signifie que la station est au sommet d'une colline ou se trouve sur un relief particulier.
* Un bonus à 0 signifie que la station se situe au niveau du référentiel sur le plan de l'altitude.
Du point de vue de l'analyse de données, les individus étudiés sont les stations. Il y a 168 variables qui correspondent aux 168 heures d'une semaine.

Au cours de ce projet, nous allons étudier ces jeux de données. Pour ce faire, nous réaliserons une analyse descriptive de nos données dans une première partie. Dans un second temps, nous verrons s'il est possible d'en réuire la dimension. Puis nous éttudirons les possibilités de classifications des données. Enfin, nous interprèterons et comparerons nos résultats avant de présenter nos conclusions.

## To do list
- Notebook R : Changer les interprétations en fonction de l'odre des graphiques, explliquer pourquoi l'ordre peut être différent de Python, màj l'interprétation 4 qui a été modifiée sur Python

- Diagramme heure station 6h altitude : ajouter carte pour mettre en avant d'éventuelles corrélations avec des lieux stratégiques de Paris (graphiques à rajouter en dessous : peut être un seul graphique sur trois su rune carte permet de mettre en avant les idées principales ?) 
- Comparer les méthodes de classification.
- Les classes ne sont pas numérotées pareil, ça pose des problèmes pour la comparaison
- Représentation du K-means sur plusieurs plans factoriels différents (voir machine Learning tp HAR)

- Pour le clustering : https://bokeh.org/ 

V- Conclusion 
