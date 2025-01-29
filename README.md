# Projet_Power_BI
Analyse des DPE des Logements dans le Rhône

# Objectif de l'application

L'application suivante est un outil de suivi des performances énérgétiques des logements du Rhône. Elle vous présente les étiquettes DPE les plus installées, les consommations en énergie ainsi que leurs coûts.

# Traitement des données :

Les données recueillies en fichier csv sur le site de l'ADEME ont été traité dans l'environnment Power Query de Power Bi. Les différentes manipulations effectuées sont :

- Pour la recueil : Rstudio avec une boucle FOR qui va intérroger l'API ramène des données qui alimentent dans un fichier csv qui par la suite deviendra notre base de données (les données ont été filtré sur le code postal du code à savoir *69%*)

- Power Query :
    Nettoyage: suppressions des colonnes inutiles, transformations des données, Changements du type de colonnes, colonne calculée et conditionnelle.

  # Visualisations interactives

  Une analyse détaillée

  Une cartographie du nombre de logement par code postal

  Une comparaison entre deux villes (Lyon et Villeurbanne)

# Indicateurs clés de performance

-Consommation

-Coût énergétique

Nos sources :

  -Contxte de l'étude : https://defis.data.gouv.fr/defis/65b76f15d7874915c8e41298
  
  -API des logements neufs : https://data.ademe.fr/datasets/dpe-v2-logements-neufs/api-doc
  
  -API des logements existants : https://data.ademe.fr/datasets/dpe-v2-logements-existants/api-doc
  
  -Exemple maquette Figma : DataPharma

# Lien POWER BI :
https://app.powerbi.com/links/m5LkVufUFB?ctid=a51a6642-5911-4306-a13c-f4731ab9c63f&pbi_source=linkShare


# Maquette Figma : 
https://www.figma.com/design/SQTDi0YeaCO2qtKXRLOUsD/DPE_Muriel_Mesmin?node-id=0-1&t=UZST3irPMjIhyobB-1

# Lien vidéo youtube :

https://youtu.be/PeywNH6hYnw?feature=shared
  
