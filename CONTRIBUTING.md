# Contribuer à PHARE

## Langue

La langue de travail, des issues, des pull requests et de la documentation est le français.

Les noms d'API, types, symboles, variables, messages de protocoles et termes techniques établis peuvent rester en anglais lorsqu'il est préférable de suivre les conventions de l'écosystème utilisé.

## Principes

Avant de modifier un dépôt :

1. identifier la source de vérité de l'artefact concerné ;
2. vérifier les interfaces et consommateurs affectés ;
3. éviter toute duplication d'un modèle, protocole, pilote ou contrôleur déjà canonique ailleurs ;
4. lier les pull requests concernées entre elles lorsqu'un changement traverse plusieurs dépôts ;
5. ne jamais introduire de mécanisme qui arme ou commande implicitement du matériel réel.

La branche de référence est `main`. Les contributions significatives passent par une branche courte, une pull request et une revue.

## Sécurité robotique

Aucun script d'installation, d'ouverture de projet, de CI ou de test standard ne doit armer des moteurs, acquitter silencieusement un défaut, écrire une calibration, modifier un zéro mécanique ou lancer un mouvement réel.

## Décisions d'architecture

Les décisions structurantes doivent être documentées dans un ADR de `phare-docs`.

La création d'un nouveau dépôt doit être justifiée par une responsabilité autonome, une interface consommable, des tests et un cycle de vie réellement indépendants.
