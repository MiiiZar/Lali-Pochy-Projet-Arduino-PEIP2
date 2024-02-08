# Rapport de Projet Arduino : Véhicule 4 Roues Motrices pour Stockage et Livraison de Cargaison

## Introduction
Ce rapport présente le développement d'un véhicule à quatre roues motrices, conçu pour stocker et livrer des cargaisons. Le contrôle de ce véhicule est assuré via Bluetooth, permettant une manipulation à distance à partir d'un téléphone mobile.

## Avancement du Projet

### Conception du Châssis
En raison de contraintes de temps, nous avons choisi de prioriser la construction du châssis. Nous avons abandonné nos premières idées au profit d'un châssis en bois, fabriqué manuellement. Nous avons découpé une pièce rectangulaire de bois au format A5 à l'aide d'une scie sauteuse, en utilisant une chute de bois disponible au fab lab. De même, nous avons découpé une planche destinée à basculer pour déposer les colis.

### Installation de la Charpente
Nous avons installé une charnière reliant les deux planches pour les lier par une liaison pivot. Cette configuration permettra à la planche de basculer pour déposer les colis de manière pratique.

### Intégration de la Communication Bluetooth
Nous avons travaillé sur la réception d'informations via Bluetooth, ce qui a finalement été réalisé avec l'aide d'un camarade. Notre système est désormais capable de recevoir des informations via une application émettant en Bluetooth. Nous avons réussi à commander une LED grâce à cette communication sans fil.

### Défis Rencontrés
Cependant, nous avons rencontré des difficultés lors de la tentative de commande des moteurs, qui sont connectés à un pont en H. Malgré nos efforts, les moteurs ne se sont pas mis en marche. Ils émettent un bruit semblant indiquer une tentative de démarrage, mais aucun mouvement n'est observé. Il semble que le courant atteignant les moteurs soit insuffisant pour entraîner leur rotation. Malgré l'aide d'un professeur et de quelques camarades, nous n'avons pas pu résoudre ce problème avant la fin de la séance.

## Conclusion
En conclusion, malgré les progrès réalisés dans la conception du châssis et l'intégration de la communication Bluetooth, des défis subsistent quant au contrôle effectif des moteurs. Nous continuerons à travailler sur ces aspects pour améliorer le fonctionnement global du véhicule.

