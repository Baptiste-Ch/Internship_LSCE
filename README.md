# Internship_LSCE
Réalisé dans le cadre du stage Master 1 Sciences de l’Océan, de l’Atmosphère et du Climat de l’Université Lyon1, ce projet vise à utiliser les sorties de modèles de paléoclimats PMIP (Paleoclimate Modeling Intercomparison Project). Une grande partie de ce travail fut consacré à développer des outils et des méthodes pour utiliser efficacement les résultats des modèles PMIP. Ensuite, ces derniers ont été utilisés pour 3 thèmes de travail distincts :

-	L’étude de la Température d’Air de Surface et d’Humidité Relative de Surface dans les zones sources d’évaporation associés au site EPICA Dome C (EDC) en Antarctique de l’Est.
-	L’étude de la température locale de surface (Ts) et d’altitude de condensation (Tc) du site EPICA Dome C.
-	L’étude des précipitations dans les zones de forte productivité primaire équatoriale.


L’ensemble des scripts de ce projet sont présentés selon un ordre décousu mais chaque script correspond à un intérêt scientifique particulier :
	
-	Antarctica.ipynb : Petit script pour réaliser une carte de l’Antarctique (sans aucune donnée requise)
-	Buizert.ipynb : Script orienté sur l’étude de la température de surface (Ts) et d’altitude de condensation (Tc) sur la zone EDC. Après une mise en commun des données, de nombreux affichages sont proposés.
-	GPP.ipynb : Script orienté sur l’étude des précipitations dans les zones de productivité primaire (GPP).
-	Temperature_gradient.ipynb : Ancien orienté sur l’étude de Ts et Tc sur la zone EDC. Ce dernier est moins intéressant et moins complet que Buizert.ipynb.
-	Variables_ponderees.ipynb : Script utilisé pour étudier la Température de l’Air de Surface ou l’Humidité Relative de la zone d’évaporation associée à EDC. Ce script permet aussi de découper une zone en sous-zones et de faire des calculs de pondérations en automatique pour chaque sous-zone.
-	Anomalies_all_models.ipynb : Script pour sortir les cartes de n’importe quelle variable/modèle/période pour les versions PMIP3 et PMIP4. + Script pour plot l’anomalie moyenne par latitude.
-	functions.ipynb : Script regroupant toutes les fonctions ayant été créées pour généraliser certains processus du projet.


NB : Sans accès aux environnements associés aux données de l’IPSL (Institut Pierre Simon Laplace) ces scripts ne peuvent pas être tournés.
