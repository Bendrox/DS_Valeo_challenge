# DS_Valeo_challenge :car:


J'applique XG Boost pour une problématique de classification en explorant 7 différentes méthodes de recherches d'hyperparamètres (HalvingGridSearchCV, BayesSearchCV, RandomizedSearchCV, GridSearchCV, HalvingRandomSearch, Optuna, Hyperplot), 3 méthodes d'imputation des valeurs manquantes (Mice, Forest Impute) et du FE pour booster les performances. Le dataset choisi est celui de l'entreprise Valeo et provient de l'ENS Challenge'.


L'excercice consiste a prévoir si les pièces sont defectueuses (ou pas) en fonction de plusieurs mesures (variables).

A premiere vue, le dataset présente deux difficultés majeures : 
- Un prédicteur fortement déséquilibré
- Des valeurs manquantes sur une des variables du dataset

Le lien vers le challenge : https://challengedata.ens.fr/participants/challenges/36/

Le travail de recherche : ValeoML.ipynb
