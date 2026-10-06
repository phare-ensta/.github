<img width="1280" height="720" alt="PHARE" src="https://github.com/user-attachments/assets/4ac55c9b-a3bc-4cf4-b624-1602f09cc2b9" />

# PHARE

**PHARE** signifie **Plateforme Humanoïde Autonome de Recherche et d'Expérimentation**.

PHARE est un projet étudiant de robotique humanoïde de l'ENSTA. Le projet développe une plateforme complète et modulaire couvrant le bas du corps, le torse, les bras, les mains, la tête, la perception, l'interaction humain-robot, le contrôle, la simulation et l'apprentissage.

## Dépôts PHARE

### Robot et ingénierie

- [`phare-manifest`](https://github.com/phare-ensta/phare-manifest) : composition des robots, bancs, workspaces et versions ;
- [`phare-docs`](https://github.com/phare-ensta/phare-docs) : documentation technique et décisions ;
- [`phare-interfaces`](https://github.com/phare-ensta/phare-interfaces) : données et protocoles partagés ;
- [`phare-description`](https://github.com/phare-ensta/phare-description) : modèle logiciel du robot ;
- [`phare-hardware`](https://github.com/phare-ensta/phare-hardware) : mécanique, électronique et intégration physique ;
- [`phare-firmware`](https://github.com/phare-ensta/phare-firmware) : code des microcontrôleurs ;
- [`phare-sdk`](https://github.com/phare-ensta/phare-sdk) : accès matériel côté calculateur principal ;
- [`phare-system`](https://github.com/phare-ensta/phare-system) : estimation, contrôle et supervision temps réel ;
- [`phare-simulation`](https://github.com/phare-ensta/phare-simulation) : simulation physique et validation virtuelle ;
- [`phare-learning`](https://github.com/phare-ensta/phare-learning) : entraînement et évaluation des modèles appris ;
- [`phare-ros2`](https://github.com/phare-ensta/phare-ros2) : perception, navigation, manipulation et HRI sous ROS 2 ;
- [`phare-tools`](https://github.com/phare-ensta/phare-tools) : outils d'ingénierie, bancs, calibration et diagnostic.

### Pilotage et communication

- [`phare-planning`](https://github.com/phare-ensta/phare-planning) : représentation Git du planning approuvé ;
- [`phare-dashboard`](https://github.com/phare-ensta/phare-dashboard) : PHARE Project Manager ;
- [`phare-website`](https://github.com/phare-ensta/phare-website) : site public du projet.

### R&D expérimentale

- [`phare-lab-template`](https://github.com/phare-ensta/phare-lab-template) : point d'entrée pour créer un nouveau PHARE Lab ;
- [`phare-labs`](https://github.com/phare-ensta/phare-labs) : registre des Labs actifs et historique des Labs clôturés.

Les dépôts de travail `phare-lab-<mission>` sont créés à la demande et ne sont pas listés ici individuellement.

## Pour contribuer

- Une idée ou une solution est encore à explorer : créer un **PHARE Lab** depuis [le formulaire de création](https://github.com/phare-ensta/phare-lab-template/issues/new?template=create-lab.yml).
- Le travail à réaliser est déjà clairement rattaché au robot : utiliser le guide [Où placer le code et les artefacts PHARE](https://github.com/phare-ensta/phare-docs/blob/main/docs/getting-started/repository-routing.md).
- Pour comprendre le projet avant de contribuer : commencer par la [vue d'ensemble PHARE](https://github.com/phare-ensta/phare-docs/blob/main/docs/system/project-overview.md).

L'objectif est simple : les Labs servent à explorer librement ; les dépôts techniques servent à intégrer ce qui a été retenu.
