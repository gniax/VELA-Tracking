# VELA Tracking

Projet de fin de deuxième année de BTS SN-IR, réalisé sur 9 semaines.  
L’objectif était de concevoir un système de suivi de régates en temps réel, permettant également à chaque participant de revoir sa course via une interface web.

![](https://i.imgur.com/hPafaeH.png)

## Contexte et objectif

Pourquoi développer ce type de système alors qu’il existe déjà des solutions de suivi de régates ?

Les solutions existantes reposent généralement sur des technologies GPS/GPRS, avec un coût d’abonnement parfois élevé.  
L’objectif de ce projet était donc de concevoir une alternative plus économique, capable de récupérer la position de chaque bateau et de chaque balise, ainsi que la vitesse des bateaux, puis de transmettre ces données à un bateau central chargé de les traiter.

Pour la récupération des coordonnées et de la vitesse, nous avons utilisé des modules GPS, dont le coût se limite à l’achat du matériel.  
Pour la transmission des données, le système repose sur deux technologies de communication : le Wi-Fi et le XBee.

## Équipe

Le projet a été réalisé par une équipe de 7 étudiants, répartis en deux groupes :

- un groupe de 4 étudiants en charge de la partie Wi-Fi ;
- un groupe de 3 étudiants en charge de la partie XBee.
