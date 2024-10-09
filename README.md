Projet de gestion d'allumage et d'extinction de modules avec RTC et EEPROM
Ce projet permet de contrôler l'allumage et l'extinction de deux modules en utilisant une horloge temps réel (RTC) et la mémoire EEPROM pour stocker les paramètres. Il utilise un Wemos D1 Mini configuré en mode point d'accès, permettant une interaction via une interface Web depuis n'importe quel smartphone ou ordinateur connecté au réseau local du Wemos.

Fonctionnalités principales :

Contrôle de deux modules : Allumage et extinction programmés des modules via des horaires configurables.
Horloge RTC : Utilisation du module RTC DS3231 pour garder l'heure exacte même après un redémarrage.
EEPROM : Sauvegarde et récupération des heures d'allumage/extinction pour assurer la persistance des données après redémarrage.
Interface Web intuitive : Configuration facile des horaires via une page Web accessible localement.
Point d'accès Wi-Fi : Le Wemos crée son propre réseau Wi-Fi pour permettre l'accès à l'interface Web sans avoir besoin d'un routeur externe.
