# Accords mets et vins 

# https://www.data.gouv.fr/fr/datasets/accords-mets-et-vins/

# Métadonnées

- Open Data Commons Open Database License (ODbL) 
- mise à jour le 19 février 2016
- créée le 20 décembre 2013 
- Nom du mets
- Nom du vin

# Étapes du travail

- Suppression des colonnes inintéressantes
- Classement par ordre alphabétique en fonction des noms de mets
- Application du filtre
- Corrections sur les lignes qui comportaient plusieurs vins pour un mets (ajout de lignes pour le même mets, une pour chaque vin proposé)
- Corrections orthographiques
- Suppression d'une ligne où aucun de nom de vin n'était inscrit, seulement un prix
- Suppression de tout ce qui n'est pas du vin, de la bière, du cidre ou du champagne
- Création de filtres par type de plat et couleur de vins pour attribuer des catégories de plats et de vins dans deux nouvelles colonnes
- Suppression des doublons
- Sélection de 365 lignes parmis le tableau (tri trop long)
- Création de tableau croisé dynamique pour obtenir des valeurs numériques

# Visualisation

- Exploration de RawGraphs, résultat non concluant
- DataWrapper mouline à l'infini et ne donne rien
- Passage sur Tableau public, réalisation d'une visualisation

# Rendu final

[Lien de la visualisation](https://public.tableau.com/profile/marie.ganter#!/vizhome/Metsetvins/Feuille1)
