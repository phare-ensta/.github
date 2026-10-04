# Politique de sécurité

PHARE comporte du logiciel, de l'électronique de puissance et des actionneurs capables de produire des mouvements physiques.

Toute vulnérabilité logicielle, fuite de secret, possibilité d'armement involontaire, contournement d'autorité, défaut de validation de commande ou comportement pouvant créer un risque matériel doit être signalé aux responsables du projet avant publication détaillée.

Ne jamais inclure de clé, mot de passe, jeton, adresse privée de banc ou autre secret dans une issue publique.

Principes minimaux :

- l'ouverture d'une connexion ou d'un workspace ne doit pas activer le robot ;
- les commandes physiques passent par une autorité explicitement définie ;
- les chaînes matérielles de sécurité restent indépendantes des outils de développement ;
- les essais sur matériel réel identifient clairement la configuration, le banc, les limites et les moyens de mise en sécurité.

Cette politique ne remplace pas les procédures d'essais et de sécurité mécanique du projet.
