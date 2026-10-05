<!-- ELUCENIA technical documentation · controle-da-asma-gina · fr · no clinical/professional/rights approval -->

# Contrôle des symptômes de l’asthme (GINA)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/controle-da-asma-gina)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Symptômes diurnes plus de 2 fois par semaine

`diurno`

### Réveil nocturne dû à l’asthme

`noturno`

### Recours au traitement de secours (SABA) plus de 2 fois par semaine

`alivio`

### Limitation des activités due à l’asthme

`limit`

## Édition de la méthode

GINA stratégie 2021 : contrôle sur 4 semaines, 4 questions ; SABA de secours ; 0/1–2/3–4

## Formule documentée

Sur les 4 dernières semaines, compter : symptômes diurnes \> 2×/semaine ; réveil nocturne par asthme ; SABA de secours \> 2×/semaine (hors usage avant exercice) ; limitation d’activité.

0 = contrôlé · 1–2 = partiellement contrôlé · 3–4 = non contrôlé.

## Limites et population

L’évaluation GINA 2021 calculée ici couvre le contrôle des symptômes au cours des quatre dernières semaines chez l’adulte et l’enfant de plus de 5 ans, avec une question de soulagement portant sur le SABA. Ce compte n’évalue pas tout le risque futur d’exacerbation, la fonction pulmonaire, les comorbidités, la technique d’inhalation ou l’observance. Le contrôle symptomatique et la sévérité de l’asthme ne sont pas équivalents. L’adaptation du matériel reste soumise aux conditions de droits du titulaire.

## Références

- [Reddel HK et al. Global Initiative for Asthma Strategy 2021: executive summary and rationale for key changes. Eur Respir J, 2022.](https://doi.org/10.1183/13993003.02730-2021)

- [Global Initiative for Asthma (GINA). Global Strategy for Asthma Management and Prevention (relatório anual).](https://ginasthma.org/reports/)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
