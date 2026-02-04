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
Quelques captures au cas ou le lien est inactif:
<img width="1916" height="1071" alt="image" src="https://github.com/user-attachments/assets/73706d0a-c77e-4ccd-89e4-ecf49edb3ab7" />

<img width="1718" height="857" alt="image" src="https://github.com/user-attachments/assets/8ce7c125-dbe8-4ecf-a71e-2aa0eefb094a" />

<img width="1733" height="821" alt="image" src="https://github.com/user-attachments/assets/04f48323-1bd1-4eb5-9080-82c17c92f184" />

<img width="1766" height="727" alt="image" src="https://github.com/user-attachments/assets/67728fb2-93fb-4630-bc97-9d608b981bb7" />

<img width="1430" height="695" alt="image" src="https://github.com/user-attachments/assets/56bad9bc-4f9e-439d-bee5-acf1da867db9" />

<img width="1506" height="702" alt="image" src="https://github.com/user-attachments/assets/c2879ff4-2325-4a58-8109-3352c9cbeb77" />

<img width="1078" height="754" alt="image" src="https://github.com/user-attachments/assets/0d59bd2b-d0ca-46ea-852e-9dcee764fcc1" />

<img width="1497" height="782" alt="image" src="https://github.com/user-attachments/assets/fb031519-f6d7-45f7-aeea-852ad75b98e6" />

# Maquette Figma : 
https://www.figma.com/design/SQTDi0YeaCO2qtKXRLOUsD/DPE_Muriel_Mesmin?node-id=0-1&t=UZST3irPMjIhyobB-1

# Lien vidéo youtube :

https://youtu.be/PeywNH6hYnw?feature=shared
  
