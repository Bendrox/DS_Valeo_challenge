# DS_Valeo_challenge :car:
En cours de construction

Je relève le défi de battre le gagnant de la compétition 'ENS Challenge' sur le dataset de Valeo avec l'utilisation exclusive d'XG Boost pour de la classification supervisée en explorant plusieurs méthodes de recherche d'hyperparamètres.

L'excercice est de prévoir si les pièces sont defectueuses (observations) ou pas en fonction de plusieurs mesures (variables).

Le dataset présente deux diffucultés majeurs : 
- Un prédicteur fortement déséquilibré
- Des valeurs manquantes sur une des variables du dataset

Le lien vers le challenge : https://challengedata.ens.fr/participants/challenges/36/

Ci dessous le classement des 5 premiers participants (métrique roc_auc) : 

<img width="813" alt="Capture d’écran 2023-09-26 à 23 14 37" src="https://github.com/Bendrox/DS_Valeo_challenge/assets/145064474/58fd5d4c-848c-483d-bb2b-4bbe907de7dd">
Source : https://challengedata.ens.fr/participants/challenges/36/ranking/public

La méthode n°4 de recherche d'hyperparamètres permet deja de battre le gagant de la compétition (avec score 0.7745)
