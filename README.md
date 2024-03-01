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
- Notebook R : (finir partie I) transcrire partie 2 ACP
- mettre à jours graph boxplot
- ACP : 
    * Hypothèses : rédiger pour les dernières composantes, faire une analyse globale.
    * Vérification hypothèses : 
	- rédiger/mieux présenter le début de l'étude des corrélations
	- étude des corrélations avec la variable en altitude pour chaque composante
	- créer des variables pour chaque/certaines heures de la journée (avec moyenne),  avec les moyennes journalières,... et étudier les corrélations avec les premières composantes (pourquoi pas tester des "courbes" de corrélations)
	- etude des dimensions supérieures à 3 : ajouter d'une variable pour la dim4? 
        - calcul des erreurs/résidus
        - affichage des nouvelles variables sur carte 
- Diagramme heure station 6h altitude : ajouter carte pour mettre en avant d'éventuelles corrélations avec des lieux stratégiques de Paris (graphiques à rajouter en dessous : peut être un seul graphique sur trois su rune carte permet de mettre en avant les idées principales ?) 
- Diagramme Etude de la temporalité du chargement moyen au cours de la semaine : rajouter une analyse sur les différences de hauteurs de pics observés entre le début de semaine (lundi/mardi) et la fin de semaine (jeudi/vendredi)
- ACP : développer les interprétations
- ACP : faire le graphe des corrélations

- Interprétations : pour la dim 4 : automatiser test altitude et appliquer aux autres dim

Suite du plan  
III- Etude des possibilités de classification
IV- Interprétation et comparaison des résultats 
V- Conclusion 
