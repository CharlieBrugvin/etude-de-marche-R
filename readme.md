*Ce projet a été réalisé dans le cadre de la formation [Data Analyst](https://openclassrooms.com/fr/paths/65-data-analyst), sur la plateforme OpenClassrooms.*

## Etude de marché

### Introduction

Dans ce projet, j'ai réalisé une étude de marché pour une entreprise fictive spécialisée dans la vente de poulets. Le but était de déterminer les pays les plus propices à une insertion.

Tout d'abord, j'ai collecté des données publiques de différentes sources sur le régime alimentaire, la population, la géographie et l'économie des pays du monde.

Après avoir fusionné et nettoyé les données, j'ai effectué un clustering (CAH) pour grouper les pays ainsi qu'une ACP pour les visualiser. Après interprétation des clusters en fonction de leurs centroïdes et des composantes principales, j'ai sélectionné le groupe de pays les plus propices et ai réitéré.
Cela m'a permis au final de sélectionner cinq pays.

J'ai alors présenté leurs données clefs telles que le PIB/hab, l'indice de risque économique, la population, le prix local de production du poulet et la quantité annuelle de volaille importée par habitant.

<br>

:arrow_forward: [Voir ma présentation des résultats](présentation.pdf)

:notebook: [Notebook : Nettoyage des données](https://htmlpreview.github.io/?https://github.com/CharlieBrugvin/etude-de-marche-en-R/blob/master/2.preparation_donnees.html)

:notebook: [Notebook : Analyse exploratoire](https://htmlpreview.github.io/?https://github.com/CharlieBrugvin/etude-de-marche-en-R/blob/master/4.analyse_exploratoire.html)

<br>

### Organisation des sources

3 dossiers :
- `1.donnees` : les données initiales du projet
- `3.donnees_propres` : les données nettoyées du projet 
- `5.resultats` : graphiques et données générées lors de l'étude
    
2 R notebooks :
- `2.preparation_donnees.Rmd`
- `4.analyse_exploratoire.Rmd`
