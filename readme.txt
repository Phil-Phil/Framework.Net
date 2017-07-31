# Framework.Net
Librairies, Fonctions, Classes .NET

Publication libre de droits de certaines parties du framework spécifiquement développé pour mon projet personnel Nano Database.


NanoDB :
Il s'agit d'une suite logicielle de stockage et d'interrogation de données sous windows.


Spécification :
  - Gestion d'une base de données bureautique dite 'In-Memory' de type NoSql pouvant gérer plusieurs milliards de lignes.
  - Réduction de l'espace physique occupé de 65% à 95%.
  - Aucune gestion d'indexes (pas de surplus pour référencer des Pages/Lignes d'informations).
  - Totalement multi-processing.
  - Pas de limite en nombre de lignes/colonnes. (enfin si, un entier signé de 32 bits pour les col. et 64 pour les lignes)
  - Informations conservées dans l'ordre d'entrée. (aucune altération de l'information d'origine)
  - Sécurité renforcée sur 3 niveaux (algorithme de stockage dynamique, encryption et habilitations utilisateurs)
  - Prise en charge des certificats x509.
  - Interface Wysiwing de documentation, qualification et d'administration des données.
  - Requêteur visuelle d'interrogation des données.
  - Module de statistiques (data-mining, scoring, machine-learning)
  - Module d'analyse spatiale (représentation et analyse géographique).
  - Module d'interface Microsoft Excel.
  
  
Exemple: 
  Fichier INSEE du rencensement de la population au niveau détail
  
    Source : 5 057 957 375 octets (données brutes textuelles)
    NanoDB :   885 445 676 octets (données brutes textuelles)


Cela permet d'interroger une base de données de plusieurs centaines de millions de lignes à partir d'un simple support USB. Pas d'extraire la base entière ! (même si possible avec autorisation).

L'objectif étant de pouvoir diffuser les informations (et uniquement celles mises à jour) d'un infocentre de manière simple et sécurisée via des fichiers ultra-légés à un ensemble d'utilisateurs qui exploiteront alors la puissance de leur ordinateur personnel pour leur propre exploitation.
