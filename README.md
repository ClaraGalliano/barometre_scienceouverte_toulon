Le baromètre national de la science ouverte (BSO) a été développé par l'équipe "Ingénierie et sciences des données" du Ministère de l'enseignement supérieur et de la recherche dès 2018.
En 2019, Laetitia Bracco a proposé une méthodologie simplifiée afin de permettre aux établissements de développer des déclinaisons locales : https://gitlab.com/Cthulhus_Queen/barometre_scienceouverte_universitedelorraine/-/tree/master
Face à l'engouement des établissements (https://barometredelascienceouverte.esr.gouv.fr/declinaisons/bso-locaux) et grâce à une collaboration avec l'Université de Lorraine, l'équipe du MESR propose aujourd'hui une démarche simple pour la création de déclinaison locale : https://barometredelascienceouverte.esr.gouv.fr/declinaisons/comment-realiser-bso-local 

Si vous souhaitez utiliser l'ancienne méthode, vous devez suivre les étapes suivantes : 

1) Téléchargez l'ensemble du baromètre sur le bureau en utilisant le bouton "Download". Dé-zippez l'archive.
2) Installez la suite Anaconda Navigator (https://www.anaconda.com/products/individual).
3) Lancez Anaconda et sélectionnez Jupyter Lab. Le dossier du baromètre téléchargé sur le bureau apparaît.
4) Remplacez les données de l'Université de Toulon par celles de votre établissement. 
La liste des requêtes utilisées est dans le fichier "requetes_bdd".
Les extractions dans les bases de données doivent se faire exactement comme c'est expliqué dans le notebook qui s'appelle "nettoyage_donnees".
Il faut effacer le contenu du dossier 'outputs' pour enlever les graphiques existants (mais conserver le dossier vide).
5) Dans le dossier qui est sur le bureau, enlever les fichiers toulonnais dans le dossier Data/raw et les remplacer par les vôtres. 
Attention, il faut reproduire très exactement le nommage des fichiers. Dans le code toulonnais par exemple, le fichier 2016 du Web of Science 
s'appelle "wos_toulon_2016". Remplacez les occurrences de "toulon" par le nom de votre établissement.
6) Ouvrir le notebook "nettoyage_donnees". Remplacer toutes les occurrences de "toulon" par le nom de l'établissement (attention : utiliser le même nom que pour les extractions de bases de données).
7) Exécutez le notebook "nettoyage_donnees" en lisant bien les instructions à chaque étape.
8) Ouvrir le notebook "barometre_universite_toulon". Remplacer toutes les occurrences de "toulon" par le nom de l'établissement (attention : utiliser le même nom que pour les extractions de bases de données). Vous pouvez aussi renommer le notebook.
7) Exécutez le notebook "barometre_universite_toulon" en lisant toutes les instructions.
8) Exécutez le notebook "clustering" en lisant toutes les instructions.
9) Les graphiques ont été automatiquement générés dans le dossier Data/outputs.
