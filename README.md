# TP-RAID
# TP RAID – Tolérance de panne et performances

## Objectif

Comprendre le fonctionnement des principaux niveaux RAID et leur utilité dans une infrastructure informatique.

Le RAID permet de regrouper plusieurs disques afin d’améliorer les performances, la disponibilité ou la tolérance de panne selon le niveau utilisé.

## Contexte

Les données sont une ressource essentielle pour une organisation.  
Une panne de disque peut provoquer une perte de données ou une interruption de service.

Le RAID permet de limiter l’impact d’une panne matérielle, mais il ne remplace pas une sauvegarde.

## Niveaux étudiés

| RAID | Fonctionnement | Tolérance de panne | Capacité utilisable |
|---|---|---|---|
| RAID 0 | Entrelacement | Aucune | 100 % |
| RAID 1 | Miroir | 1 disque | 50 % |
| RAID 5 | Parité simple | 1 disque | N - 1 |
| RAID 6 | Double parité | 2 disques | N - 2 |

## RAID 0

Le RAID 0 répartit les données sur plusieurs disques.  
Il améliore les performances, mais ne protège pas les données.  
Si un disque tombe en panne, toutes les données sont perdues.

## RAID 1

Le RAID 1 duplique les données sur deux disques.  
Il offre une bonne tolérance de panne, mais la capacité utilisable est divisée par deux.

## RAID 5

Le RAID 5 répartit les données et la parité sur plusieurs disques.  
Il offre un bon compromis entre performance, capacité et sécurité.

## RAID 6

Le RAID 6 fonctionne comme le RAID 5, mais avec une double parité.  
Il peut supporter la panne de deux disques.

## Point important

Le RAID n’est pas une sauvegarde.  
Il protège principalement contre certaines pannes matérielles, mais pas contre la suppression accidentelle, les ransomwares ou la corruption de fichiers.

## Compétences mobilisées

- Compréhension du stockage
- Tolérance de panne
- Comparaison RAID
- Disponibilité des données
- Notions de sauvegarde

## Conclusion

Ce TP m’a permis de comprendre les différences entre les niveaux RAID et l’importance de choisir une solution adaptée aux besoins de l’entreprise.
