# HapPy-Factory
Sur la base des résultats du sondage World Happiness Report (Gallup World Poll), nous tentons de modéliser le score de bonheur moyen de chaque nation à l'aide d'autres questions du même sondage et de variables complémentaires (religions, régions, PIB, corruption, ...).

Code and notebook :
-------------------
WHPy-Creation Dataframes.ipynb : Creation de la/des dataframe utile à l'etude<br>
WHPy - Data-Vizualisation.ipynb : Data viz<br>
TBD : Machine learning<br>
WHPy-1st model LinearRegression.ipynb : Test de la régression linéaire sur les données initiales<br>
WHPy-1st dataset models.ipynb : Test de multiples modèles (excepté la regression linéaire) sur les données initiales<br>
WHPy-dataset_all models.ipynb : Test de modèles sur toutes les données<br>
WHPy-regions models.ipynb : modelisations pour 2 regions du monde particulieres<br>
WHPy-Lasso Models.ipynb : Modèle retenu et comparaison de séries de variables<br>
Previous_Life_Ladder_function.ipynb : 

Created data set :
----------------
**DataFrames exploités : <br>**
whr_NoNA.csv : Données du WHR sans données manquantes<br>
whr_NoNA_all.csv : Données complémentaires ajoutées <br>
whr_NoNA_all_part.csv : Données complémentaires réduites avec nombre de lignes maximales<br>
whr_NoNA_all_part_topia.csv : whr_NoNA_all + ajout des nations utopia et dystopia*<br>
whr_NoNA_all_topia.csv : whr_NoNA_all_part + ajout des nations utopia et dystopia*<br>
\* utopia et dystopia sont des nations fictives avec les meilleurs et pires scores chaque année à toutes les questions du sondage.
<br><br>
**DataFrames intermédiaires : <br>**
Religion_based_on_whr_NoNA.csv : <br>
Corrup_based_on_whr_NoNA.csv : <br>
Democracy_based_on_whr.csv : <br>
Demography_based_on_whr_NoNA.csv : <br>
Inequality_based_on_whr_NoNA.csv : <br>

Original data set :
-------------------
world-happiness-report.csv, <br>
world-happiness-report-2021.csv :<br>
Données du World Happiness Report (Gallup World Poll) 2015/2021
Rapport mondial sur le bonheur (en anglais : World Happiness Report) propose une mesure du bonheur publiée par le Réseau des solutions pour le développement durable des Nations unies chaque année depuis 2012.

Added data set :
----------------
democracy_index.csv : Indice de démocratie 2020  - The Economist<br>
Indicateur évalué en fonction de 60 critères concernant le pluralisme, les libertés et la culture civique
Classification en type : Démocratie, démocratie imparfaite, hybride, dicature<br>
https://en.wikipedia.org/wiki/Democracy_Index
<br><br>
demographics.csv : Données démographiques - United States Census Bureau<br>
https://www.census.gov/
<br><br>
inequalities.csv : Coefficient de Gini (indice d’inégalité) - 2020<br>
https://worldpopulationreview.com/country-rankings/wealth-inequality-by-country
<br><br>
sql-pays.csv : dictionnaire des noms des pays FR-EN
<br><br>
Proportion des religions et des croyances dans les pays du monde en 2010 - Pew Research Center (scraping)
https://fr.wikipedia.org/wiki/Liste_des_pays_par_religion
<br><br>
Indice de perception de la corruption 2012/2020 - Transparency International (scraping)
https://fr.wikipedia.org/wiki/Indice_de_perception_de_la_corruption
