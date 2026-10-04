# Contribuer à PHARE

## Langues et conventions de nommage

La documentation, les descriptions techniques, les discussions détaillées et le contenu rédactionnel du projet sont rédigés en français.

Les éléments de traçabilité Git sont rédigés en anglais :

- messages de commit ;
- titres de pull request ;
- titres d'issues ;
- noms de branches.

Les noms d'API, types, symboles, variables et termes techniques établis restent en anglais lorsqu'ils suivent les conventions de l'écosystème utilisé.

## Conventional Commits

Tous les nouveaux commits suivent Conventional Commits :

```text
<type>(<scope>): <subject>
```

Types usuels :

```text
feat fix docs refactor test build ci chore perf style revert
```

Le scope est optionnel. Le sujet est court, en anglais, sans point final.

Exemples :

```text
feat(firmware): add domain watchdog
fix(system): reject stale joint feedback
docs(arms): document wrist interface
test(simulation): add wheel LQR regression case
chore: initialize repository
```

Les titres de pull request utilisent de préférence le même format, notamment lorsqu'un squash merge reprend le titre de la PR comme message de commit.

Les titres d'issues restent en anglais, mais ne sont pas obligatoirement au format Conventional Commits.

## Avant de modifier un dépôt

1. Identifier la source de vérité de l'artefact concerné.
2. Vérifier les interfaces et consommateurs affectés.
3. Éviter toute duplication d'un modèle, protocole, pilote ou contrôleur déjà canonique ailleurs.
4. Lier les pull requests concernées entre elles lorsqu'un changement traverse plusieurs dépôts.
5. Ne jamais introduire de mécanisme qui arme ou commande implicitement du matériel réel.

## Branches et contributions

La branche de référence est `main`.

Les branches sont courtes et nommées en anglais, par exemple :

```text
feat/arms-calibration
fix/domain-timeout
docs/controller-core-adr
test/lqr-sil-regression
```

Les contributions significatives passent par une pull request et une revue.

## Pull requests

Le titre est en anglais. Le corps peut être rédigé en français.

Une pull request doit préciser le problème traité, la solution retenue, le périmètre impacté, les tests exécutés, les risques et les éventuelles dépendances avec d'autres pull requests.

Un changement de protocole, de modèle robot, de mapping matériel ou d'autorité de commande doit expliciter sa stratégie de compatibilité ou de migration.

## Sécurité robotique

Aucun script d'installation, d'ouverture de projet, de CI ou de test standard ne doit armer des moteurs, acquitter silencieusement un défaut, écrire une calibration, modifier un zéro mécanique ou lancer un mouvement réel.

## Décisions d'architecture

Les décisions structurantes doivent être documentées dans un ADR de `phare-docs`.

La création d'un nouveau dépôt doit être justifiée par une responsabilité autonome, une interface consommable, des tests et un cycle de vie réellement indépendants.
